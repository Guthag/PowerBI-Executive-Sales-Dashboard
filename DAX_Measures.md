# DAX Measures

## Total Sales

```DAX
Total Sales =
SUM(Sales[Sales Amount])
```

---

## Total Cost

```DAX
Total Cost =
SUM(Sales[Total Product Cost])
```

---

## Total Profit

```DAX
Total Profit =
[Total Sales] - [Total Cost]
```

---

## Profit Margin

```DAX
Profit Margin =
DIVIDE([Total Profit],[Total Sales],0)
```