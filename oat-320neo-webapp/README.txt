OAT / ALTITUDE PROFILE WEB APP

Files:
- index.html: responsive app and graph
- manifest.webmanifest: home-screen app settings
- service-worker.js: offline cache
- icon-192.png and icon-512.png: icons

INSTALL ON IPHONE
1. Upload all files in this folder to the root of an HTTPS static site. GitHub Pages or Netlify can be used.
2. Open the published HTTPS URL in Safari while online.
3. Wait a few seconds, then reload once if needed.
4. In Safari, tap Share > Add to Home Screen. Enable Open as Web App if offered, then tap Add.
5. Launch the home-screen app once while online. Test by enabling Airplane Mode and reopening it.

Service workers require HTTPS (except localhost). Opening index.html directly from Files is a preview, not a reliable offline installation.

DATA / CALCULATION
This app reproduces the two profiles and formulas visible in the provided workbook. Default target altitudes: A320NEO 35000 ft; G-UJEA / B / C 25000 ft. Formula rounding is implemented to match Excel ROUNDUP (away from zero) and ROUNDDOWN (toward zero). Please independently validate before operational use.

SAFETY
This is an unofficial recreation and not a certified performance tool. Confirm all data, formula logic, units, rounding and applicability against approved aircraft/operator documentation. Do not use as the sole basis for flight planning, dispatch, or aircraft operation.
