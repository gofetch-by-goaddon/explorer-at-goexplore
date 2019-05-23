# explorer-at-goexplore

A comprehensive user interface for Goexplore. Enables webshop owners to navigate through the data you collect from them with Gofetch.

# Index recommendations

### Used by countries\__show, delivery_methods\__show, payment_methods\__show, stock_messages\__show, statuses\__show, variants\__show

```json
{
  "klass": "webshops",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by countries\__index, orders\__show

```json
{
  "klass": "countries",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "name": 1
      }
    }
  ]
}
```

### Used by countries\__show

```json
{
  "klass": "countries",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by customers\__show

```json
{
  "klass": "customers",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by customers\__show

```json
{
  "klass": "orders",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "customer_id": 1,
        "datetime_first": -1
      }
    }
  ]
}
```

### Used by delivery_methods\__index

```json
{
  "klass": "delivery_methods",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "name": 1
      }
    }
  ]
}
```

### Used by delivery_methods\__show, orders\__show

```json
{
  "klass": "delivery_methods",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by payment_methods\__show, orders\__show

```json
{
  "klass": "payment_methods",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by statuses\__show, orders\__show

```json
{
  "klass": "statuses",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by orders\__index

```json
{
  "klass": "orders",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "datetime_first": -1
      }
    }
  ]
}
```

### Used by orders\__show, variants\__show

```json
{
  "klass": "orders",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by orders\__show

```json
{
  "klass": "shipments",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "order_id": 1,
        "datetime": 1
      }
    }
  ]
}
```

### Used by orders\__show

```json
{
  "klass": "order_lines",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "order_id": 1,
        "_id": 1,
      }
    }
  ]
}
```

### Used by orders\__show, variants\__show

```json
{
  "klass": "variants",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by orders\__show, products\__show, variants\__show

```json
{
  "klass": "products",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by payment_methods\__index

```json
{
  "klass": "payment_methods",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "name": 1
      }
    }
  ]
}
```

### Used by products\__index

```json
{
  "klass": "products",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "sku": 1
      }
    }
  ]
}
```

### Used by products\__show

```json
{
  "klass": "variants",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "product_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by products\__show, stock_messages\__show, variants\__show

```json
{
  "klass": "stock_messages",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "_id": 1
      }
    }
  ]
}
```

### Used by statuses\__index

```json
{
  "klass": "statuses",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "name": 1
      }
    }
  ]
}
```

### Used by stock_messages\__index

```json
{
  "klass": "stock_messages",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "name": 1
      }
    }
  ]
}
```

### Used by variants\__show

```json
{
  "klass": "order_lines",
  "indexes": [
    {
      "key": {
        "company_id": 1,
        "variant_id": 1
      }
    }
  ]
}
```
