Setup:
 - Navigate to ngx-entended-pdf-viewer-compatibility-with-ion-router-outlet
 - Install ionic/cli - npm install --save-dev @ionic/cli
 - Install dependencies (ionic app deps, and ngx-extended-pdf-viewer) - npm i
 - Run - npx ionic serve

Steps to reproduce:
 - Tab 1 will load properly (with a demo pdf that is viewable - https://mozilla.github.io/pdf.js/web/compressed.tracemonkey-pldi-09.pdf)
 - Navigating to Tab 2 or Tab 3 (uses the same component) and should render the pdf there too
 - Instead, no pdf is rendered and the following error is logged to the console:
   - "offsetParent is not set -- cannot scroll"
   - See image below

<img width="678" height="242" alt="image" src="https://github.com/user-attachments/assets/503c119a-62f6-4c48-ac37-fa32f8d0ade7" />
