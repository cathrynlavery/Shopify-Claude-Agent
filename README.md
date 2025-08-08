# Shopify Developer Agent for Claude

A comprehensive Shopify development agent for Claude that provides expert assistance with theme development, Hydrogen headless commerce, Shopify Functions, metaobjects/metafields, B2B wholesale, and the latest 2024-2025 Shopify features.

## 🚀 Features

### Core Capabilities
- **Online Store 2.0** - Full theme architecture and Liquid templating expertise
- **Hydrogen & Oxygen** - Headless commerce with React-based framework
- **Shopify Functions** - Custom backend logic with <5ms execution
- **Metafields & Metaobjects** - Advanced data structures and list types
- **B2B Wholesale** - Company accounts, volume pricing, net terms
- **AI Features** - Shopify Magic, Sidekick, Semantic Search
- **Checkout Extensibility** - Modern checkout UI extensions (checkout.liquid deprecated)
- **Performance Optimization** - Core Web Vitals, lazy loading, critical CSS

## 📦 Installation

### For Claude Desktop App

1. Clone this repository or download the `shopify-developer.md` file
2. Place the file in your Claude agents directory:
   ```bash
   # macOS/Linux
   ~/.claude/agents/shopify-developer.md
   
   # Windows
   %USERPROFILE%\.claude\agents\shopify-developer.md
   ```

3. The agent will be automatically available in Claude

### For Claude.ai (Web)

Copy the contents of `shopify-developer.md` into a new conversation as context, or use it as a custom instruction.

## 💬 Example Prompts

### Theme Development

```
"Create a product card component that displays metafield data for ingredients and allergens, with responsive images and quick-add to cart functionality"

"Build a collection page filter system using metaobjects for custom attributes like material, season, and fit"

"Optimize my product page for Core Web Vitals - it's currently scoring 45 on mobile"
```

### Metafields & Metaobjects

```
"Set up a metaobject structure for customer testimonials with fields for rating, review text, customer name, and product reference"

"Create a product specification system using metafields that supports both single values and lists for technical products"

"How do I display list-type metafields for product features with proper Liquid syntax?"
```

### Shopify Functions

```
"Create a Shopify Function that applies tiered discounts based on cart quantity: 10% for 5+, 15% for 10+, 20% for 20+ items"

"Build a delivery customization function that adds express shipping only for orders over $100"

"Implement a cart transform function that automatically adds a free gift when customers purchase 3 items from a specific collection"
```

### Hydrogen Development

```
"Create a Hydrogen 2.0 product listing page with infinite scroll and filter functionality"

"Build a custom cart drawer component in Hydrogen with line item editing and discount code support"

"How do I implement Optimistic UI in Hydrogen for cart updates?"
```

### B2B Wholesale

```
"Set up volume pricing tiers for B2B customers with quantity breaks at 10, 50, and 100 units"

"Create a wholesale catalog with custom pricing that's only visible to logged-in B2B customers"

"Implement net payment terms with 30-day invoicing for approved wholesale accounts"
```

### Checkout Extensibility

```
"Create a checkout UI extension that offers gift wrapping with a custom message field"

"Build a checkout validation function that prevents checkout if certain products are shipped to restricted regions"

"Add a trust badge section to checkout showing security certifications and guarantees"
```

### Performance & SEO

```
"Implement lazy loading for product images with native loading attribute and intersection observer fallback"

"Add structured data for product reviews with aggregate ratings for rich snippets"

"Optimize Liquid loops in my collection template - it's timing out with 500+ products"
```

### Shopify Flow Automation

```
"Create a Flow workflow that tags customers as VIP when they've spent over $1000 lifetime"

"Build an automation that sends products for review when inventory drops below 10 units"

"Set up automated order routing based on customer location metafields"
```

## 🎯 Best Use Cases

1. **Theme Customization** - Modifying existing themes or building from scratch
2. **App Integration** - Connecting third-party apps with themes
3. **Performance Optimization** - Improving site speed and Core Web Vitals
4. **Data Architecture** - Planning metafield and metaobject structures
5. **Headless Commerce** - Building with Hydrogen or custom frontends
6. **B2B Solutions** - Implementing wholesale features
7. **Migration Projects** - Moving from other platforms to Shopify
8. **Custom Functionality** - Adding features beyond standard Shopify

## 🛠️ Agent Configuration

The agent is configured with:
- **Model**: Sonnet (optimized for code generation)
- **Focus**: Practical implementation over theory
- **Output**: Complete, working code with examples
- **Knowledge**: Current through 2024-2025 Shopify features

## 📚 What's Included

- Complete Liquid templating patterns
- Online Store 2.0 architecture guidance
- Shopify Functions examples
- Hydrogen 2.0 components
- Checkout UI Extension patterns
- B2B implementation strategies
- Performance optimization techniques
- Latest API changes and deprecations

## ⚠️ Important Notes

### Recent Deprecations (2024)
- `checkout.liquid` deprecated August 13, 2024 - use Checkout Extensibility
- `metafieldDelete` mutation replaced with `metafieldsDelete`
- Private/public metafield permissions removed

### Platform Limitations
- 100 variant limit per product
- 200 metafields per resource type
- Shopify Functions must execute in <5ms
- Theme files: 50MB total, 2MB per file

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the agent:

1. Fork the repository
2. Create a feature branch
3. Add your improvements (new patterns, updated features, bug fixes)
4. Submit a pull request

Please ensure your contributions:
- Include working code examples
- Reference official Shopify documentation
- Are tested on actual Shopify stores
- Follow the existing format structure

## 📄 License

MIT License - feel free to use this agent for any purpose

## 🔗 Resources

- [Shopify Dev Docs](https://shopify.dev)
- [Shopify Changelog](https://changelog.shopify.com)
- [Hydrogen Documentation](https://hydrogen.shopify.dev)
- [Shopify Partner Academy](https://academy.shopify.com)
- [Dawn Theme](https://github.com/Shopify/dawn)

## 💡 Tips for Best Results

1. **Be Specific** - Include plan tier (Basic/Plus), theme name, and specific requirements
2. **Provide Context** - Share existing code, file structure, or current implementation
3. **Mention Constraints** - Specify performance budgets, browser support, or business rules
4. **Test Incrementally** - Test code in development stores before production
5. **Check Documentation** - Verify against latest Shopify docs as platform evolves rapidly

## 🌟 Star This Repository

If you find this agent helpful, please star the repository to help others discover it!

## 👋 Author

Created by **Cathryn Lavery**
- Twitter: [@cathrynlavery](https://twitter.com/cathrynlavery)
- Shopify Store: [BestSelf.co](https://bestself.co)

---

*Last Updated: August 2025 | Includes Shopify Winter '24 & Summer '24 Edition Features*