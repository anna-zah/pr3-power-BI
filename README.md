# pr3-power-BI
Power BI dashboard project demonstrating sales, logistics, payments, and reviews analytics with DAX, modeling, UX/UI, and interactive visualisations.
# Power BI Analytics Dashboard

## Project Objective
Develop a comprehensive Power BI dashboard to demonstrate skills in data modeling, DAX calculations, UX/UI design, and interactive visualizations across sales, logistics, payments, and customer reviews.

## Tools
Power BI Desktop

## Key Skills Demonstrated
- Prototype and UX/UI design
- Selection and formatting of appropriate charts
- Scalar and iterative DAX calculations, calculated columns
- Data modeling, table relationships, and data transformation
- Power BI functionalities: hierarchies, groups, filters, cross-filtering, tooltips, detail pages, content switching, bookmarks, buttons, pop-ups

## Project Workflow

### 1. Interface
- Establish a consistent theme: colors, fonts, and style
- Organize content logically into sections/tabs
- Provide interactive elements: buttons, bookmarks, pop-ups, info blocks, navigation
- Add clear titles and labels for all dashboard components

### 2. Metrics
Sales Metrics
- Average ticket  
- Revenue (sum of completed deals)  
- Open deal value  
- Conversion rate (Sales / Leads)  
- Geographic ratings  
- Active client base (unique clients with at least 1 completed deal)  

Logistics Metrics
- On-time delivery rate  
- Delivery cost per unit  
- Average order processing time  
- Average order cycle time  

### 3. Data Modeling
- Establish relationships between tables  
- Denormalize olist_orders_dataset in Power Query to create a sales funnel  
- Remove unnecessary fields  
- Create a calculated column in olist_products_dataset to categorize products (custom groups and logic)

### 4. Functionality
- Date filter (dynamic calendar) and two additional metric filters  
- Year-over-year comparison (growth/decline)  
- Content switching via DAX  

### 5. Visualizations
- Four tabs: Sales, Logistics, Payments, Reviews  
- Sales funnel controlled by calendar on Sales tab  
- Order dynamics or growth (by sum and count) on Sales tab  
- Map visualization on any tab with selectable metrics  

### 6. Independent Analytics (Optional)
- Payments tab  
- Reviews tab  
- Additional metrics and visualizations at analyst’s discretion

## Deliverables
- Fully functional Power BI dashboard (.pbix)  
- Interactive charts and KPIs  
- Demonstration of advanced DAX, modeling, and UX/UI design
