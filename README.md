## Project Workflow

### 1. Data Preparation (Power Query)

- Imported and cleaned tables including **Orders**, **Customers**, and **OrderDetails**.
- Set correct data types and removed unnecessary columns.
- Created new time-based columns such as **OrderYear** and **OrderMonth**.

### 2. Data Modeling (Power Pivot & DAX)

- Built a relational **Data Model** connecting tables via **OrderID** and **CustomerID**.
- Developed key **DAX measures**:
  - Total Sales
  - Total Orders
  - Total Quantity
  - Average Order Value

### 3. Interactive Dashboard

- Designed a **single-page interactive dashboard** with a clean layout.
- Added **KPI cards** to display key metrics:
  - Total Sales
  - Total Orders
  - Total Quantity
- Created **PivotCharts** to visualize sales trends by:
  - Time
  - Country
  - Category
- Integrated **Slicers** and **Timelines** for dynamic filtering.
