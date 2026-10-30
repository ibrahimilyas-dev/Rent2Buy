# Rent to Buy Website

A custom responsive rent-to-buy car website with no-code inventory management via Pages CMS.

## First-time setup

1. Create a new **private or public GitHub repository** and upload the contents of this folder (not the outer folder).
2. In Netlify choose **Add new project > Import an existing project > GitHub**, select the repository. Netlify reads `netlify.toml` and uses `npm run build`, publishing `dist`.
3. Visit https://pagescms.org and sign in with GitHub. Grant it access to the repository. The `.pages.yml` file tells Pages CMS how to edit your car listings and business settings.
4. In Pages CMS, open **Vehicle Listings**. Add a car, set its weekly price, upload its main and extra photos, and choose Available, Reserved or Sold. Click **Save**. Pages CMS commits changes to GitHub; Netlify then builds and publishes the new version automatically. This is not instant: allow a minute or two for deployment.
5. In **Business Settings**, change the placeholder business name, WhatsApp number, phone, email and address. The WhatsApp number must use international digits only, e.g. `447700900123`.
6. To add the large hero photo, upload a JPG named `hero-car.jpg` to `public/images/` via GitHub. For the lifestyle photo, upload `lifestyle.jpg` to the same folder. These two decorative images are not part of the car listings. The owner can also manage car listing photos directly in Pages CMS.
7. Remove the three sample cars from Pages CMS and replace them with real inventory before advertising the site.

## Image locations

- Main banner: `public/images/hero-car.jpg` (ideally a transparent-background vehicle PNG or a clean JPG)
- Lifestyle section: `public/images/lifestyle.jpg`
- Car listing images: upload through Pages CMS; files go into `public/images/` and links are added to each vehicle automatically.
- Business logo: upload in **Business Settings** through Pages CMS.

## Important

- The sample car listings and prices are **demonstration data**. Replace them before launch.
- Website copy deliberately avoids claiming no credit checks, guaranteed approval, free servicing, warranty, tax or ownership after a fixed number of weeks. Confirm the client's actual contractual and regulatory position before making any of those claims.
- This is an enquiry website, not a payment or signed-contract platform.
- Pages CMS uses GitHub login. Give the client the necessary repository permissions and Pages CMS access, rather than sharing your GitHub password. Check Pages CMS and Netlify current plan limits and access controls before going live.
- For a client who should not access your own GitHub account, use a dedicated GitHub organisation/repository and invite them with the least privileges required.
