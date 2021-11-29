---
name: Testing
description: Text
conclusion: Text
image: workflow.png
tags:
  - Requests
stage: Automation
type: sync
order: 1
status: draft
maturity: optimized
version: 2021-11-24
areas:  

  - label: Folders
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Pre-Request Scripts
        label: Pre-Request Scripts    
      - name: Test Scripts
        label: Test Scripts                                                    

  - label: Requests
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Pre-Request Scripts
        label: Pre-Request Scripts    
      - name: Test Scripts
        label: Test Scripts  

  - label: Response
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Test Results
        label: Test Results   
        
  - label: Automation
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Monitors
        label: Monitors
      - name: Pipelines
        label: Pipelines        
        
  - label: Observability
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Reporting
        label: Reporting  
      - name: APM
        label: APM          
        
discussion: 
yaml: 
roles:
  - Backend
  - Data
  - DevOps
  - Engineering
  - Frontend
  - Mobile
  - Product
  - Security
  - Writers
...
