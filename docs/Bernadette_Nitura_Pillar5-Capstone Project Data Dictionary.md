

| Variable | Type | Description | Allowed Values | Notes |
| ----- | ----- | ----- | ----- | ----- |
| **InvoiceNo** | Numeric (Integer) | Invoice number composed of a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. | 1-999999 | Alphanumeric detected |
| **StockCode** | Numeric (Integer) | Product (item) code composed of a 5-digit integral number uniquely assigned to each distinct product. | 1-99999 | Alphanumeric detected |
| **Description** | Text (String) | Product name | abc | Null value detected |
| **Quantity** | Numeric (Integer) | The quantities of each product (item) per transaction | 1-99999 | Negative value detected |
| **InvoiceDate** | Numeric | Invoice Date and time. The date and time when each transaction was generated. | MM/DD/YYYY HH:MM |   |
| **UnitPrice** | Numeric (Float) | Product price per unit | 1-99999 | Negative value detected |
| **CustomerID** | Numeric (Float) | Customer number composed of a 5-digit integral number uniquely assigned to each customer. | 1-99999 | Null value detected |
| **Country** | Text (String) | Country name. The name of the country where each customer resides. | abc |   |

