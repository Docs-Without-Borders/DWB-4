DWB-4 STAGING BUILD - Test before main deploy

This is the staging version for dwb-4.vercel.app

STEPS TO UPDATE DWB-4 ON VERCEL (Windows):
1. Unzip this folder
2. Go to vercel.com, open your dwb-4 project
3. Drag and drop the unzipped folder via Vercel dashboard or use Vercel CLI: vercel --prod
4. Wait for deployment, visit https://dwb-4.vercel.app
5. Check the gold staging banner and complete the 3-item checklist:
   - Founder photo loads
   - AR button works on phone (View in Your Room)
   - FAQ accordion opens
6. When all green, tell me and I will flip canonical to www.documentswithoutborders.org and package the MAIN deploy zip

What's inside:
- index.html = staging site with noindex (so Google doesn't index staging)
- assets/founder-oswald.jpg
- assets/dwb_globe.glb (Green=Hague, Blue=Non-Hague)
- robots.txt, sitemap.xml, vercel.json

Main site deploy will be same content but with canonical back to documentswithoutborders.org and index,follow robots.
