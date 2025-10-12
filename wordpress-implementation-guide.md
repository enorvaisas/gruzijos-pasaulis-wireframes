# WordPress/Breakdance Implementation Guide

## Overview
This guide provides step-by-step instructions for implementing the new Gruzijos Pasaulis website structure using WordPress with Breakdance page builder.

## WordPress Setup Requirements

### Essential Plugins
1. **Breakdance** - Page builder
2. **WooCommerce** - E-commerce functionality
3. **Yoast SEO** - SEO optimization
4. **Contact Form 7** - Contact forms
5. **Events Calendar** - Event management
6. **Custom Post Types UI** - Custom post types
7. **Advanced Custom Fields** - Custom fields
8. **WP Rocket** - Performance optimization

### Theme Recommendations
- **Astra** (lightweight, Breakdance compatible)
- **GeneratePress** (fast, customizable)
- **Custom theme** (if budget allows)

## Page Structure Implementation

### 1. Homepage (`homepage-wireframe.html`)
**Breakdance Elements Needed:**
- Hero Section with background image
- Service cards grid
- Featured products carousel
- Upcoming events list
- About preview section
- Blog preview
- Contact CTA
- Footer with social links

**Custom Fields:**
- Hero title and subtitle
- Service descriptions
- Featured product selection
- Event dates and details

### 2. Kulinariniai Mokymai (`cooking-classes-wireframe.html`)
**Breakdance Elements:**
- Page hero with stats
- Service types comparison
- Learning outcomes grid
- Calendar/events section
- Testimonials carousel
- FAQ accordion
- CTA section

**Custom Post Type: "Events"**
- Event title
- Date and time
- Price
- Capacity
- Description
- Booking form integration

### 3. E-parduotuvė (`e-shop-wireframe.html`)
**WooCommerce Integration:**
- Product categories
- Product grid with filters
- Search functionality
- Shopping cart
- Checkout process

**Product Categories:**
- Prieskoniai (Spices)
- Namų tekstilė (Home Textiles)
- Paveikslai (Paintings)
- Aksesuarai (Accessories)
- Dovanos (Gifts)

### 4. Blogas (`blog-wireframe.html`)
**WordPress Blog Features:**
- Blog post grid
- Category filtering
- Tag cloud
- Search functionality
- Newsletter signup

**Custom Post Type: "Blog Posts"**
- Featured image
- Category selection
- Tags
- Reading time
- Author information

### 5. Kontaktai (`contact-wireframe.html`)
**Breakdance Elements:**
- Contact information cards
- Contact form
- Google Maps integration
- FAQ section
- Social media links

## SEO Implementation

### Technical SEO
1. **URL Structure:**
   - `/kulinariniai-mokymai/` (not `/kulinariniai-mokymai-page/`)
   - `/menas/paveikslai/` (hierarchical)
   - `/blogas/receptai/` (category-based)

2. **Schema Markup:**
   - Organization schema on all pages
   - Event schema for classes/dinners
   - Product schema for shop items
   - Article schema for blog posts
   - LocalBusiness schema for contact page

3. **Meta Tags:**
   - Unique titles for each page
   - Descriptive meta descriptions
   - Proper heading hierarchy (H1, H2, H3)
   - Alt text for all images

### Content SEO
1. **Target Keywords:**
   - Primary: "Gruzijos virtuvė", "kulinariniai mokymai Kaune"
   - Secondary: "degustacinės vakarienės", "Gruzijos kultūra"
   - Long-tail: "kaip gaminti chačapuri", "Gruzijos prieskoniai"

2. **Local SEO:**
   - Google My Business optimization
   - Local keywords: "Kaunas", "Gruzijos kultūra Lietuvoje"
   - Address and contact info consistency

## Performance Optimization

### Image Optimization
- WebP format for all images
- Lazy loading implementation
- Responsive images (different sizes for mobile/desktop)
- Image compression (80-85% quality)

### Caching Strategy
- WP Rocket for page caching
- CDN integration (Cloudflare recommended)
- Database optimization
- Minification of CSS/JS

### Mobile Optimization
- Mobile-first design approach
- Touch-friendly buttons (minimum 44px)
- Fast loading on mobile networks
- Responsive typography

## User Experience (UX) Best Practices

### Navigation
- Clear hierarchy with dropdown menus
- Breadcrumb navigation
- Search functionality
- Mobile hamburger menu

### Conversion Optimization
- Clear call-to-action buttons
- Booking forms with minimal fields
- Trust signals (testimonials, certifications)
- Social proof (customer reviews)

### Accessibility
- WCAG 2.1 AA compliance
- Keyboard navigation support
- Screen reader compatibility
- High contrast ratios
- Alt text for images

## Content Management

### Custom Post Types
1. **Events** - For classes and dinners
2. **Artists** - For artist profiles
3. **Products** - WooCommerce integration
4. **Blog Posts** - Standard WordPress posts
5. **Videos** - For video lessons

### Custom Fields (ACF)
- Event dates and pricing
- Artist biographies
- Product specifications
- Video descriptions and links
- SEO fields (meta descriptions, keywords)

## Analytics and Tracking

### Google Analytics 4
- Event tracking for bookings
- E-commerce tracking for shop
- Goal conversions setup
- User behavior analysis

### Google Search Console
- Sitemap submission
- Performance monitoring
- Index status checking
- Mobile usability testing

## Security Implementation

### WordPress Security
- Strong passwords and 2FA
- Security plugins (Wordfence)
- Regular updates
- Backup strategy (UpdraftPlus)

### SSL and HTTPS
- SSL certificate installation
- HTTPS redirect
- Mixed content fixing
- Security headers

## Launch Checklist

### Pre-Launch
- [ ] All pages created and content added
- [ ] Forms tested and working
- [ ] E-commerce functionality tested
- [ ] Mobile responsiveness checked
- [ ] SEO optimization completed
- [ ] Analytics tracking installed
- [ ] Security measures implemented

### Post-Launch
- [ ] Google Search Console setup
- [ ] Google My Business updated
- [ ] Social media integration
- [ ] Performance monitoring
- [ ] User feedback collection
- [ ] Regular content updates planned

## Maintenance Plan

### Weekly Tasks
- Content updates (blog posts, events)
- Social media integration
- User feedback monitoring

### Monthly Tasks
- Performance optimization review
- SEO performance analysis
- Security updates
- Backup verification

### Quarterly Tasks
- Complete site audit
- User experience testing
- Content strategy review
- Technical SEO audit

## Budget Considerations

### Essential Costs
- WordPress hosting: €20-50/month
- Breakdance license: €99/year
- Premium plugins: €200-300/year
- SSL certificate: €50-100/year

### Optional Enhancements
- Custom theme development: €2000-5000
- Professional photography: €500-1500
- Content creation: €1000-3000
- Marketing campaigns: €500-2000/month

This implementation guide provides a comprehensive roadmap for creating a modern, SEO-optimized, and user-friendly website that will significantly improve the current site's performance and user experience.
