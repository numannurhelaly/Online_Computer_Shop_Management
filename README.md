 How to Run in XAMPP

1. Extract this folder into:

```text
C:/xampp/htdocs/razon_online_computer_shop_final/
```

2. Start **Apache** and **MySQL** from XAMPP.
3. Open phpMyAdmin:

```text
http://localhost/phpmyadmin
```

4. Import this file:

```text
database/computer_shop_final_with_sample_data.sql
```

5. Open the project:

```text
http://localhost/online_computer_shop_final/
```

## Demo Login

| Role | Email | Password |
|---|---|---|
| Admin | `numan@shop.com` | `12345678` |
| Customer | `numan1@shop.com` | `12345678` |



## Main Features

- User registration, login, logout, profile update and remember-me support
- Admin dashboard
- Category and sub-category management
- Brand management
- Product CRUD with image upload
- Customer product browse, category/brand filter and AJAX search
- Cart add, update and remove
- Product review add/delete
- Checkout with Cash on Delivery, bKash, Nagad and DBBL/Rocket
- Admin order accept/delete
- Admin customer and review management

## Important Folders

```text
config/                 Database and session helpers
controllers/            Route/controller logic
models/                 Database functions
views/                  UI pages
api/                    AJAX endpoints
public/css/             CSS
public/js/              JavaScript/AJAX validation
public/uploads/         Product/profile uploads
database/               SQL files
docs/                   Documentation and task ownership
task_contributions/     Original task snapshots from razon.zip
```

## CSS / UI Update

The final app uses separated external CSS files inside `public/css/`:

- `style.css` - main CSS loader
- `base.css` - variables, reset, typography, background
- `layout.css` - navbar, container, hero, footer
- `components.css` - buttons, forms, tables, alerts, badges
- `pages.css` - product, cart, review, order, admin page styles
- `responsive.css` - tablet/mobile layout

Final app PHP views do not use inline CSS. Styling is controlled from the external CSS files.
