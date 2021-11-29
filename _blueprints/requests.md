---
name: Requests
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

  - label: Requests
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: HTTP Methods
        label: HTTP Methods
      - name: URL
        label: URL    
      - name: Query Parameters
        label: Query Parameters   
      - name: Authorization
        label: Authorization   
      - name: Request Headers
        label: Request Headers  
      - name: Request Body
        label: Request Body  
      - name: Request Settings
        label: Request Settings                                               

  - label: Response
    description: Text
    image: images/lifecycle-arrow-define.png
    elements:
      - name: Response Body
        label: Response Body
      - name: Cookies
        label: Cookies 
      - name: Response Headers
        label: Response Headers    
      - name: Visualizer
        label: Visualizer  
      - name: Response Network
        label: Response Network   
      - name: Response Time
        label: Response Time  
        
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
