# Albany Aegis Initiative Website

## Project Overview

The Albany Aegis Initiative (AAI) is a civic technology and public safety platform focused on supporting crime prevention, anti-corruption, and urban resilience in Albany, New York. This website serves as a central hub for transparency tools, research publications, and data visualizations, targeting policymakers, community members, and law enforcement.

The name **"Aegis"** symbolizes the initiative's mission to protect the city and its institutions.

## Core Mission Areas

The initiative and this website support four key pillars:

- **Data-Driven Decision-Making**: Presenting crime trends, recidivism metrics, and predictive models.
- **Behavioral Insight**: Communicating research on criminal psychology, restorative justice, and community interventions.
- **Technological Integration**: Highlighting the use of surveillance, crime mapping, digital forensics, and real-time analytics.
- **Economic Diversification**: Advocating for development and employment pipelines to address socioeconomic causes of crime.

## Website Objectives

- **Inform**: Provide clear summaries of research, reports, and updates.
- **Visualize**: Embed interactive maps, dashboards, and data graphics.
- **Engage**: Offer channels for community involvement.
- **Establish Trust**: Present a credible, secure, and authoritative web presence.

## Technical Details

- **Repository**: [https://github.com/jgwalsh02134/AAI-Gemini](https://github.com/jgwalsh02134/AAI-Gemini)
- **Deployment**: GitHub Pages (**domain TBA**)
- **Development Tools**: Visual Studio Code (Mac M1), Git, GitHub

**Technologies Used**:
- HTML5  
- Tailwind CSS (for styling and responsive layout)  
- Google Fonts (Lora, Source Sans Pro)  
- Chart.js (for data visualizations)  
- SVG (for heraldic assets)

## Setup and Installation

This project is a static website. To set up locally for development:

```bash
git clone https://github.com/jgwalsh02134/AAI-Gemini.git
cd AAI-Gemini
```

Open `index.html` (or any HTML file) in your web browser.

No build process or server is strictly required, as all dependencies (Tailwind CSS, Chart.js, Google Fonts) are loaded via CDN.

## Deployment

The site is deployed using GitHub Pages directly from the `main` branch of the repository.

1. Commit and push your local changes to GitHub.
2. In your GitHub repository, go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch as the source and save.

Once configured, the site will be available at `https://<your-github-username>.github.io/AAI-Gemini/` or a custom domain (**TBA**) if configured.

## File Structure

```
AAI-Gemini/
├── index.html          # Homepage
├── css/                # (Future) Custom CSS files if needed
├── js/                 # (Future) Custom JavaScript files if needed
├── images/             # (Future) Image assets
├── reports/            # (Future) Downloadable reports (e.g., Crime-Analysis-Report.pdf)
└── README.md           # This file
```

## Data Sources and Visualizations

The initiative utilizes data from verified sources, including:

- Albany Police Department FOIL data (2021–2024)
- New York State Division of Criminal Justice Services (DCJS) *(Placeholder)*
- Academic research and legal/policy analysis *(Placeholders)*

**Key visualizations** (using Chart.js):

- Total Crimes vs Arrests Over Time  
- Top Crime Neighborhoods  
- Case Closure Rates by Year  
- Top Crime Types  

These appear under the **"Recent Reports & Relevant Data"** section of the homepage.

## Future Roadmap

- Implement full content for placeholder sections (Publications, Dashboard, Contact Form)
- Integrate interactive visualizations (crime maps, dynamic charts)
- Develop a secure contact/submission form
- Refine mobile navigation and overall responsiveness
- Integrate heraldic vector assets and finalize visual identity
- Add optional dark mode toggle

## Contact

For inquiries about the Albany Aegis Initiative, please refer to the contact section on the website once it is available in a future update.

---

This README provides a comprehensive overview for contributors and developers interested in the Albany Aegis Initiative website project.