---
title: "GRANTHAE: A Peer-to-Peer Book Marketplace"
description: "A full-stack platform for renting, buying and managing books through a peer-to-peer marketplace."
publishDate: "2026-06-24"
tags: ["nodejs", "express", "mongodb", "ecommerce", "javascript"]
pinned: true
---

## Overview

GRANTHAE is a peer-to-peer library and book marketplace built to make it easier for readers to rent books from other people, buy new or pre-owned books, and manage their own digital library.

The platform brings together marketplace workflows, rental management and user account features in one application.

## What the platform includes

- **Book marketplace:** browse, search and filter books available to buy or rent
- **Peer-to-peer rentals:** users can list books and manage rental requests
- **Buying and selling:** support for new and used book listings
- **Personal library:** a place for users to manage their books
- **Cart and wishlist:** save items and manage purchase intent
- **Wallet and returns:** wallet-related flows, refunds and return management
- **Offers and coupons:** product/category offers and coupon management
- **Sales reports:** reporting features for marketplace activity
- **Payments:** payment gateway integration with Razorpay and PayPal
- **User and admin workflows:** account management and administrative controls

## Technical implementation

GRANTHAE is built with **Node.js** and **Express.js** on the server side, **MongoDB** for data storage and **EJS** for server-rendered user interfaces.

The application connects authentication and user management with book listings, cart and wishlist operations, orders, rental flows, payment processing, wallet transactions, returns and administrative features. Payment-related workflows need to remain consistent with order and wallet records.

The project was deployed on **AWS EC2**. Working on the deployment also provided practical experience with production configuration and running a Node.js application on a cloud server.

## What I learned

Building GRANTHAE helped me understand how different modules in a full-stack application depend on one another. A payment flow, for example, is connected to orders, wallet updates, refunds and the user's order history.

I gained practical experience in backend development, database operations, integrating third-party payment gateways, building marketplace workflows and deploying an application.

## Project

- **Live application:** [GRANTHAE](https://granthae.linshad.xyz/)
- **GitHub repository:** [GRANTHAE repository](https://github.com/linshadj/GRANTHAE/)

