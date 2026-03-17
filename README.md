# Crown & Mane Boutique Salon Website

## Overview
This is a simple, automated website for Crown & Mane Boutique Salon. It allows you to update services and products easily, without needing any technical knowledge.

Whenever you make changes and upload (push) them, the website updates automatically within minutes.

## How to Update Your Website

You only need to edit two files:

### 1. Update Services

Open the services.json

Example:
```JSON
[
    {
        "name": "Natural Hair Consultation",
        "price": 50
    },

    {
        "name": "Custom Coloring",
        "price": 120
    },

    {
        "name":"Hair Styling & Updos",
        "price": 80
    },

    {
        "name": "Deep Conditioning Treatment",
        "price": 60
    }
]
```

Add Services like these and save it.

### 2. Update Products

Open the file: inventory.json

Example:
```JSON

[
    {
        "name": "Shea Butter Moisturizer",
        "price": 25
    },

    {
        "name": "Argan Oil Treatment",
        "price": 40
    },

    {
        "name": "Curl Defining Cream",
        "price": 30
    },

    {
        "name": "Herbal Shampo",
        "price": 20
    }
]

```

Enter the products like these and save it.
**Notes:**
    - Keep the format exactly the same.
    - DO NOT remove commas or brackets incorrectly.
    - Prices should be numbers (no $ sign inside JSON)

---

## How to Publish Your Changes
After editing:
    1. Save the file in VS Code.
    2. Open terminal in your project root folder.
    3. Run:
```Bash
git add .
git commit -m "Updated services/products"
git push
```

That's it - no manual deployment needed.
It will auto run the pipeline and changes will be reflected in Website.

---

## How Automation Works
Every time you push changes:
    1. Github automatically checks your files
    2. It validates that your JSON files are correct
    3. If everything is valid:
        - Your website is deployed automatically
    4. If there is data validation or any error:
        - Deployment stops with red mark (to prevent breaking the site)

This ensures your website is always safe and working.

---

## How to Check if Everything Worked

1. Go to your Github Repository
2. Click on the `Actions` tab.

You will see your latest update:
    - Green = Success (website Updated)
    - Red = Error (needs fixing)

## Live Website
1. Live URL: https://saqibaltaf27.github.io/Crown-and-Mane-Boutique-Salon/
2. Github Repository: https://github.com/saqibaltaf27/Crown-and-Mane-Boutique-Salon.git 

