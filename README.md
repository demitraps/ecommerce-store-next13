
# Full Stack Next.js 13 E-Commerce Store | Next.js 13 App Router, React, Tailwind, Prisma, MySQL

This is the repository for a fully functioning [E-commerce Store](https://ecommerce-store-next13.vercel.app/).

Find the Github repository for the Admin Dashboard here: https://github.com/demitraps/ecommerce-admin-dashboard-next13

## Features

- Featured products in homepage
- View different categories
- Preview card of product
- Product page with color and size filters
- Related items
- Add to cart
- Stripe checkout
- Stripe webhooks
   
## Tech Stack

**React, Next.JS 13, TypeScript, TailwindCSS**

**Authentication:** Clerk
**Data validation:** Zod
**FileUploads:** Cloudinary
**Components:** Shadcn
**Database:** MySQL-PlanetScale with Prisma ORM

## Demo
https://ecommerce-store-next13.vercel.app/

![App Screenshot](./demo/demo.gif)


## Checkout

For demo purposes, you can use [Stripe Testing Cards](https://stripe.com/docs/testing).


## Screenshots

Homepage:

![App Screenshot](./demo/homepage.png)

Categories:

![App Screenshot](./demo/category.png)

Product preview card:

![App Screenshot](./demo/productpreview.png)

Filter by color/size:

![App Screenshot](./demo/filter.png)

Related items:

![App Screenshot](./demo/related.png)

Shopping cart:

![App Screenshot](./demo/shoppingcart.png)

Stripe:

![App Screenshot](./demo/stripe.png)

## To-Do List

- Multiple quantities per product
- Email notifications
- Video uploads
- Social icons and preview
- Contact/FAQ pages




### Prerequisites

**Node version 14.x**

### Cloning the repository

```bash
  git clone https://github.com/demitraps/ecommerce-store-next13.git
```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |