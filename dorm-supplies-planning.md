# Dorm Supplies Planning

### Basic Objects

##### User
```js
{
  id,
  email: String,
  hash: String,
  name: String,
  isAdmin: Boolean,
  address: String,
  classYear: Number,
  orders: [{
    items: [{
      itemId: String,
      quantity: Number,
      price: Number
    }],
    itemId: String,
    quantity: Number,
    purchasedDate: Date, 
    deliveryDate: Date,
    price: Number,
    isPaid: Boolean
  }]
}
```

##### Item
```js
{
  id,
  name: String,
  price: Number,
  description: String,
  quantity: Number,
  picture: String
}
```

