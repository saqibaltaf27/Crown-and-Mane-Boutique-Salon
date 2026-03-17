# Crown & Mane Boutique Salon - Automated Deployment Pipeline

## Goal
Create a professional workflow for a non-technical salon owner to update their website easily, without manual deployment or errors.

## Requirements

### 1. Website
    - One-page static HTML/CSS Website.
    - Sections:
        -> `Services` section: lists hair care services and pricing.
        -> Inventory of hair care products (inventory.json).

### 2. Validation Step
    - Every time the owner updates inventory.json and pushes to Github, the JSON should be validated automatically.
    - If the JSON in invalid, the workflow should fail and prevent deployment.

### 3. Automated Deployment
    - When changes are pushed to the main branch:
        -> Validate inventory.json
        -> Deploy the website automatically to a public host (Github Pages)

    - Deployment should require no manual intervention.

### 4. Documentation
    - A brief README explaining:
        -> How the salon owner can push updates.
        -> How the automation works.
        -> How to see successful deployment.

---

## Deliverables
1. Project ZIP: A compressed folder containing the website code and the .github/workflows directory.
2. Public Repository: A link to the public GitHub repository hosting the code.
3. Live Demo: A link to the live, deployed URL where the salon site is hosted.
4. Proof of Success: A screenshot of the GitHub Actions tab showing a successful "Green" build and deployment.