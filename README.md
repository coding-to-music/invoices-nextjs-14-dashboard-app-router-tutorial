# invoices-nextjs-14-dashboard-app-router-tutorial

# 🚀 A Dashboard App where users can create an account and manage their customers and invoices. It is based on the Next Learn Course, the official Next.js 14 tutorial 🚀

https://github.com/coding-to-music/invoices-nextjs-14-dashboard-app-router-tutorial

From / By https://github.com/josiasbudaydeveloper/nextjs-14-dashboard-app-router-tutorial

https://josiasbudaydeveloper-next-14-dashboard-app.vercel.app/dashboard

https://nextjs.org/learn/dashboard-app

https://nextjs.org/learn/react-foundations

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/invoices-nextjs-14-dashboard-app-router-tutorial.git
git push -u origin main
```

## Environment variables:

```java

```

# Dashboard App
A Dashboard App where users can create an account (with their credentials or using an OAuth provider), create customers and assign invoices to them. Invoices will be shown at the Dashboard page as a summary. This project is based on the Next Learn Course, the official Next.js 14 tutorial and created by Vercel.

> It is based on the Next Learn Course, the official Next.js 14 tutorial and created by Vercel and was created to showcase my developer skills.
> [Click here](https://nextjs.org/learn) to visit the official tutorial page.
>
> You can access the current live version of the live project and see what I'm capable of by clicking
> [here](https://josiasbudaydeveloper-next-14-dashboard-app.vercel.app/dashboard)!

![Course explainer](https://nextjs.org/_next/image?url=%2Flearn%2Fcourse-explainer.png&w=1920&q=75&dpl=dpl_DiW2ecigo2JKHD1ioFP2oTFMkZS8)

## This project is a Dashboard App that is a single page application (SPA) with client-side navigation and three main pages:
- Dashboard - A summary of all invoices.
- Invoices - A list of all invoices and the possibility of searching, creating, editing or deleting any invoice. It also has pagination at the bottom of the page.
- Customers - A list of all customers with a search bar for searching for specific customers. There's no pagination here in this version, so all customers are displayed at the same time.
- Dark Theme - Based on Tailwind.css and that only works based on the browser theme.

## Here’s everything I did in the version 2.0:
- Multiuser system
- OAuth Authentication
- Pagination for the customers, as they're going to be flexible at this version
- Dark Theme feature based on the user's browser theme
