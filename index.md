---
layout: default
title: Capsailer
---

<div class="hero-section">
  <div class="hero-content">
    <h1>Deliver Kubernetes applications to air-gapped environments</h1>
    <p>Standardize your offline application delivery with a simple, unified workflow from bundle creation to deployment without external dependencies.</p>
    <div class="cta-container">
      <a href="https://docs.capsailer.dev/getting-started/" class="cta-button">Get Started</a>
      <button class="download-button" onclick="toggleDownload()">
        Download
        <svg fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
        </svg>
        <div class="download-dropdown">
          <a href="https://github.com/capsailer/capsailer-cli/releases/latest/download/capsailer-linux-amd64.tar.gz">Linux X64</a>
          <a href="https://github.com/capsailer/capsailer-cli/releases/latest/download/capsailer-linux-arm64.tar.gz">Linux ARM64</a>
          <a href="https://github.com/capsailer/capsailer-cli/releases/latest/download/capsailer-darwin-arm64.tar.gz">Mac OS Apple Silicon</a>
          <a href="https://github.com/capsailer/capsailer-cli/releases/latest/download/capsailer-darwin-amd64.tar.gz">Mac OS Intel Chip</a>
          <a href="https://github.com/capsailer/capsailer-cli/releases/latest/download/capsailer-windows-amd64.exe.zip">Windows x64</a>
        </div>
      </button>
    </div>
  </div>
</div>

## What is Capsailer?

Capsailer is a CLI tool for delivering Kubernetes applications into air-gapped (offline) environments, built as an open-source project. It packages Helm charts and container images into portable bundles that can be easily transported and deployed in disconnected environments.

## How Does it Work?

Capsailer has three core phases: bundling, transport, and deployment. In the connected environment, you define a manifest of images and charts, which Capsailer downloads and packages into a portable bundle. After physically transferring this bundle to the air-gapped environment, Capsailer deploys a local container registry and Helm chart repository, then pushes the artifacts from the bundle to these local services.

## Core Components

<div class="component-section">
  <div class="component-card">
    <h3>Bundle Creator</h3>
    <p>Downloads and packages container images and Helm charts into a portable archive</p>
  </div>
  
  <div class="component-card">
    <h3>Registry Deployer</h3>
    <p>Sets up a local container registry and Helm chart repository in the air-gapped environment</p>
  </div>
  
  <div class="component-card">
    <h3>Artifact Pusher</h3>
    <p>Uploads images and charts to the local registry without requiring external tools</p>
  </div>
  
  <div class="component-card">
    <h3>Self-contained CLI</h3>
    <p>Operates without dependencies in the air-gapped environment</p>
  </div>
</div> 