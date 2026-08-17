# Support Source Code | Lumenboard Designer

Support Source Code is the public product and support website for **Lumenboard Designer 1.0**—a Windows desktop workspace for visual learning, diagramming, code visualization, and teaching.

The website is designed to give prospective users, partners, and investors a clear view of the current product, its operating requirements, available download paths, architecture material, support channels, and future source-code licensing opportunity.

**Live website:** [supportsourcecode.github.io](https://supportsourcecode.github.io/)

## Product overview

Lumenboard Designer 1.0 is offered as a free Windows desktop application. Its current positioning is a visual workspace that supports learning, planning, diagramming, and code visualization.

The product requires **Node.js 22.13 or newer** to run its local development server. Once started, the application is accessed locally at `http://localhost:3000`.

The site includes a product-architecture diagram and an original-source-code diagram to communicate the product’s technical direction.

## Website experience

The single-page site provides:

- A video-led introduction and application overview.
- A product card for Lumenboard Designer 1.0 and a placeholder for future applications.
- Download links for Lumenboard Designer and the required Node.js installer.
- Clear installation and manual-start instructions for Windows users.
- Product architecture and source-code diagrams.
- A future source-code purchase callout for users who want to apply their logic through an LLM provider.
- Support and community touchpoints, including WhatsApp, email, and planned social channels.

The visual presentation uses a responsive aqua-blue design with animated water-bubble accents. All animation layers are decorative and do not block user interaction.

## Source-code opportunity

Lumenboard Designer is freely downloadable for end users. The website also presents a future commercial path for the original source code, including customization and LLM-provider use cases.

The purchase control is currently labelled **Coming Soon**. The public site does not yet process source-code purchases; interested parties can contact Support Source Code directly.

## User setup and running instructions

1. Install **Node.js 22.13 or newer**.
2. Verify the local installation in Command Prompt or PowerShell:

   ```powershell
   node --version
   npm --version
   ```

3. Install and launch Lumenboard Designer 1.0.
4. If the desktop icon does not start the local server, open Command Prompt or PowerShell and run the following from the application installation directory. The product may be installed on any drive:

   ```powershell
   cd "D:\Lumenboard Designer_1.0\resources\app"
   npm run dev
   ```

5. Keep the terminal window open, wait for the server to report that it is ready, and open [http://localhost:3000](http://localhost:3000).
6. Close the terminal window or press `Ctrl+C` when finished.

## Downloads

The current website buttons link to Google Drive folders:

- [Lumenboard Designer 1.0 download](https://drive.google.com/drive/folders/16hdXBM5xP2TnsHEG0pzxtfo4RCowKDtL?usp=sharing)
- [Node.js v22.20.0 (x64) download](https://drive.google.com/drive/folders/1WYSLD4iZVf_6FfOEv6Xt1263n_GQTnlM?usp=sharing)

For production distribution, release assets hosted through GitHub Releases or an equivalent managed download channel are recommended. When a download destination changes, update the relevant `href` values in `index.html`.


## Contact and partnership enquiries

- Website: [supportsourcecode.github.io](https://supportsourcecode.github.io/)
- Email: [supportsourcecode@gmail.com](mailto:supportsourcecode@gmail.com)
- WhatsApp: [7903933705](https://wa.me/917903933705)

## Current status

The public website, product download guidance, support channels, architecture materials, and source-code interest path are in place. Direct source-code purchasing and the listed social channels remain planned additions.

© 2026 Support Source Code. All rights reserved.
