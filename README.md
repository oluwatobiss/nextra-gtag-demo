# Nextra + Gtag Demo

This is a demo site showing how to add google analytics to a [Nextra](https://nextra.site) website.

## Usage

1. Fork this repo.

2. Clone your forked copy.

3. Run `npm install` to install the predefined dependencies.

4. Deploy the site to Vercel.

5. Create a Google Analytics 4 property for the site.

6. Create a `.env.local` file in the project's root directory.

7. Add `NEXT_PUBLIC_GA_ID=G-xxxxxxxxxx` to the `.env.local` file. (**Note:** Please replace `G-xxxxxxxxxx` with your Google Analytics measurement id.)

8. Add your Google Analytics measurement id to your Vercel environment variables.

9. Once you've deployed all updates to Vercel, navigate to various pages of your live site.

10. Verify that the gtag works from your site's Google Analytics account.

## License

This project is licensed under the MIT License.
