# Shopify Developer Agent - Prompt Library

A comprehensive collection of prompts to get the most out of the Shopify Developer Agent for Claude.

## 🎨 Theme Development Prompts

### Basic Theme Customization
```
"Add a sticky header to my Dawn theme that changes background on scroll"

"Create an announcement bar that rotates between 3 messages every 5 seconds"

"Build a mega menu with product images for the main navigation"
```

### Product Pages
```
"Create a size chart modal that opens from a button on product pages, pulling data from a size_chart metafield"

"Add a 'Recently Viewed Products' section at the bottom of product pages using localStorage"

"Build a product image gallery with zoom on hover and thumbnail navigation"

"Create a sticky add-to-cart bar that appears when the main button scrolls out of view"
```

### Collection Pages
```
"Add infinite scroll to collection pages with a loading spinner"

"Create a product quick-view modal that loads product details via AJAX"

"Build a collection page sidebar filter using product metafields for brand, material, and size"

"Implement a sort dropdown that remembers user preference in sessionStorage"
```

### Cart & Checkout
```
"Create a slide-out cart drawer with quantity adjusters and remove buttons"

"Add a progress bar showing 'Free shipping at $X' in the cart"

"Build a cart upsell section recommending products based on cart contents"

"Create a gift note field that saves to order notes"
```

## 🔧 Shopify Functions Prompts

### Discount Functions
```
"Create a Function for BOGO: buy any 2 shirts, get the cheapest one 50% off"

"Build a volume discount: 10% off 3 items, 15% off 5 items, 20% off 10+ items"

"Implement a discount that gives 20% off but only for first-time customers"

"Create a bundle discount: buy product A and B together, get 25% off the total"
```

### Delivery Functions
```
"Hide express shipping for orders containing hazardous materials (using metafield)"

"Add a $15 rush processing fee for next-day delivery options"

"Create local delivery zones based on postal codes with different rates"
```

### Payment Functions
```
"Hide PayPal for orders over $3000"

"Add a 2% surcharge for credit card payments over $1000"

"Restrict payment methods based on customer tags"
```

### Validation Functions
```
"Prevent checkout if cart contains more than 5 of any single item"

"Block checkout for specific products shipping to certain states"

"Require a minimum order value of $50 for wholesale customers"
```

## 📊 Metafields & Metaobjects Prompts

### Product Metafields
```
"Set up metafields for a clothing store: material, care instructions, fit type, and sustainability info"

"Create a product ingredients list using list-type metafields with allergen highlighting"

"Build a technical specifications table using metafields for electronics products"

"Display warranty information from metafields with icon badges"
```

### Metaobjects
```
"Create a FAQ system using metaobjects with categories and search functionality"

"Build a store locator using metaobjects for location data with map integration"

"Set up a brand story timeline using metaobjects with dates, titles, and descriptions"

"Create a recipe system with metaobjects linking to products as ingredients"
```

### Dynamic Content
```
"Display different product badges based on metafield values (new, sale, limited edition)"

"Create a 'Complete the Look' section using product reference metafields"

"Build a comparison table using metafields for similar products"
```

## 🚀 Hydrogen & Headless Prompts

### Basic Hydrogen Setup
```
"Create a Hydrogen 2.0 starter with homepage, PLP, PDP, and cart"

"Set up Hydrogen with Tailwind CSS and custom fonts"

"Implement authentication in Hydrogen with customer accounts"
```

### Hydrogen Components
```
"Build a product card component with quick-add and wishlist functionality"

"Create a predictive search component with product and collection results"

"Implement a mini cart that updates optimistically"

"Build a product recommendations carousel using the Storefront API"
```

### Performance
```
"Optimize Hydrogen images with responsive sizing and lazy loading"

"Implement route-based code splitting in Hydrogen"

"Add prefetching for product pages on hover"

"Create a progressive web app with offline support"
```

## 💼 B2B & Wholesale Prompts

### B2B Setup
```
"Configure B2B wholesale with company accounts and net 30 payment terms"

"Create tiered pricing: 10% off at 10 units, 15% at 25, 20% at 50+"

"Set up a wholesale application form that creates pending B2B customers"
```

### B2B Features
```
"Display volume pricing tables only for logged-in B2B customers"

"Create a quick order form for B2B customers to add multiple SKUs at once"

"Build a reorder feature showing previous B2B orders"

"Add minimum order quantities for wholesale customers"
```

### Sales Rep Features
```
"Create a sales rep portal for placing orders on behalf of customers"

"Build a quote request system for custom B2B pricing"

"Implement customer-specific catalogs with custom pricing"
```

## 🎯 Performance & Optimization Prompts

### Speed Optimization
```
"Audit and optimize my theme for Core Web Vitals, currently scoring 40"

"Implement critical CSS for above-the-fold content"

"Lazy load all images below the fold with blur-up effect"

"Optimize third-party scripts to reduce main thread blocking"
```

### Liquid Optimization
```
"Refactor this collection template that's timing out with 500+ products"

"Optimize nested Liquid loops that are causing slow page loads"

"Implement pagination with AJAX loading for large product lists"
```

### SEO
```
"Add comprehensive schema markup for products with reviews and availability"

"Create an XML sitemap using Liquid that includes all products and collections"

"Implement hreflang tags for multi-language stores"

"Add Open Graph tags for better social sharing"
```

## 🤖 AI & Automation Prompts

### Shopify Flow
```
"Create a Flow that tags high-value customers when they pass $5000 in lifetime spend"

"Build a workflow that sends low stock alerts when inventory drops below 10"

"Automate order tagging based on shipping destination for fulfillment routing"

"Create a customer win-back flow for customers who haven't ordered in 90 days"
```

### Search & Discovery
```
"Implement predictive search with typo tolerance and synonym support"

"Create smart collections using AI-powered product categorization"

"Build a visual search feature using product images"
```

## 🛠️ Migration & Integration Prompts

### Platform Migration
```
"Create a migration plan from WooCommerce to Shopify preserving SEO"

"Map Magento 2 data structure to Shopify metafields and metaobjects"

"Build a product import template for migrating from BigCommerce"
```

### App Integration
```
"Integrate Klaviyo email signup with AJAX and success messaging"

"Add Yotpo reviews to product pages with structured data"

"Implement Recharge subscription options on product pages"

"Connect Gorgias chat widget with customer data prefill"
```

## 📱 Mobile & Responsive Prompts

### Mobile Optimization
```
"Create a mobile-first navigation with hamburger menu and search"

"Build touch-friendly product image galleries with swipe gestures"

"Optimize checkout for mobile with proper input types and autofill"

"Add a mobile app banner with smart app detection"
```

### Responsive Design
```
"Make product grids responsive: 4 columns desktop, 2 tablet, 1 mobile"

"Create a responsive table that converts to cards on mobile"

"Build a responsive video hero section with mobile fallback image"
```

## 🔒 Security & Compliance Prompts

### Security
```
"Implement content security policy headers for XSS protection"

"Add rate limiting to forms to prevent spam submissions"

"Secure customer data handling in theme JavaScript"
```

### Compliance
```
"Add GDPR-compliant cookie consent with granular controls"

"Implement age verification for restricted products"

"Create accessibility improvements for WCAG 2.1 AA compliance"
```

## 💡 Advanced Prompts

### Complex Implementations
```
"Build a product configurator with live preview and price updates"

"Create a multi-step product personalization flow with image uploads"

"Implement a store credit system using customer metafields"

"Build a referral program with unique codes and tracking"
```

### Custom Features
```
"Create a wishlist feature using customer metafields and localStorage"

"Build a product comparison tool with side-by-side features"

"Implement store-wide search with filters for products, pages, and blog posts"

"Create a back-in-stock notification system with email capture"
```

## 🎓 Learning Prompts

### Understanding Concepts
```
"Explain the difference between sections and blocks in Online Store 2.0"

"How do Shopify Functions differ from Script Editor?"

"What's the best way to structure metaobjects for a recipe website?"

"Compare Hydrogen vs traditional theme development pros and cons"
```

### Best Practices
```
"What's the recommended way to handle product variants over 100?"

"How should I structure metafields for optimal performance?"

"What's the best approach for multi-currency with B2B customers?"

"How do I properly version control a Shopify theme?"
```

## 🚨 Troubleshooting Prompts

### Debugging
```
"Debug why my cart.js AJAX calls are returning 404 errors"

"Fix Liquid error: 'Liquid error: Memory limits exceeded'"

"Resolve CORS issues with Storefront API calls"

"Fix missing translations in multi-language checkout"
```

### Performance Issues
```
"Diagnose why my collection page takes 10 seconds to load"

"Find what's causing Cumulative Layout Shift on product pages"

"Identify render-blocking resources affecting LCP"
```

---

## Pro Tips for Better Results

1. **Include Context**: "I'm using Dawn theme version 11.0.0 on Shopify Plus"
2. **Specify Requirements**: "Must work on mobile Safari and be WCAG compliant"
3. **Mention Constraints**: "Without using any apps or external services"
4. **Provide Examples**: "Similar to how Amazon shows related products"
5. **State the Goal**: "To increase average order value by 20%"

Remember: The more specific your prompt, the better the result!