
```
food-app-yt-main
├─ client
│  ├─ components.json
│  ├─ eslint.config.js
│  ├─ index.html
│  ├─ package-lock.json
│  ├─ package.json
│  ├─ postcss.config.js
│  ├─ public
│  │  └─ vite.svg
│  ├─ README.md
│  ├─ src
│  │  ├─ admin
│  │  │  ├─ AddMenu.tsx
│  │  │  ├─ EditMenu.tsx
│  │  │  ├─ Orders.tsx
│  │  │  └─ Restaurant.tsx
│  │  ├─ App.css
│  │  ├─ App.tsx
│  │  ├─ assets
│  │  │  ├─ hero_pizza.png
│  │  │  └─ react.svg
│  │  ├─ auth
│  │  │  ├─ ForgotPassword.tsx
│  │  │  ├─ Login.tsx
│  │  │  ├─ ResetPassword.tsx
│  │  │  ├─ Signup.tsx
│  │  │  └─ VerifyEmail.tsx
│  │  ├─ components
│  │  │  ├─ AvailableMenu.tsx
│  │  │  ├─ Cart.tsx
│  │  │  ├─ CheckoutConfirmPage.tsx
│  │  │  ├─ FilterPage.tsx
│  │  │  ├─ Footer.tsx
│  │  │  ├─ HereSection.tsx
│  │  │  ├─ Loading.tsx
│  │  │  ├─ Navbar.tsx
│  │  │  ├─ Profile.tsx
│  │  │  ├─ RestaurantDetail.tsx
│  │  │  ├─ SearchPage.tsx
│  │  │  ├─ Success.tsx
│  │  │  └─ ui
│  │  │     ├─ aspect-ratio.tsx
│  │  │     ├─ avatar.tsx
│  │  │     ├─ badge.tsx
│  │  │     ├─ button.tsx
│  │  │     ├─ card.tsx
│  │  │     ├─ checkbox.tsx
│  │  │     ├─ dialog.tsx
│  │  │     ├─ dropdown-menu.tsx
│  │  │     ├─ input.tsx
│  │  │     ├─ label.tsx
│  │  │     ├─ menubar.tsx
│  │  │     ├─ select.tsx
│  │  │     ├─ separator.tsx
│  │  │     ├─ sheet.tsx
│  │  │     ├─ skeleton.tsx
│  │  │     ├─ sonner.tsx
│  │  │     └─ table.tsx
│  │  ├─ index.css
│  │  ├─ layout
│  │  │  └─ MainLayout.tsx
│  │  ├─ lib
│  │  │  └─ utils.ts
│  │  ├─ main.tsx
│  │  ├─ schema
│  │  │  ├─ menuSchema.ts
│  │  │  ├─ restaurantSchema.ts
│  │  │  └─ userSchema.ts
│  │  ├─ store
│  │  │  ├─ useCartStore.ts
│  │  │  ├─ useMenuStore.ts
│  │  │  ├─ useOrderStore.ts
│  │  │  ├─ useRestaurantStore.ts
│  │  │  ├─ useThemeStore.ts
│  │  │  └─ useUserStore.ts
│  │  ├─ types
│  │  │  ├─ cartType.ts
│  │  │  ├─ orderType.ts
│  │  │  └─ restaurantType.ts
│  │  └─ vite-env.d.ts
│  ├─ tailwind.config.js
│  ├─ tsconfig.app.json
│  ├─ tsconfig.json
│  ├─ tsconfig.node.json
│  └─ vite.config.ts
├─ package-lock.json
├─ package.json
└─ server
   ├─ controller
   │  ├─ menu.controller.ts
   │  ├─ order.controller.ts
   │  ├─ restaurant.controller.ts
   │  └─ user.controller.ts
   ├─ db
   │  └─ connectDB.ts
   ├─ index.ts
   ├─ mailtrap
   │  ├─ email.ts
   │  ├─ htmlEmail.ts
   │  └─ mailtrap.ts
   ├─ middlewares
   │  ├─ isAuthenticated.ts
   │  └─ multer.ts
   ├─ models
   │  ├─ menu.model.ts
   │  ├─ order.model.ts
   │  ├─ restaurant.model.ts
   │  └─ user.model.ts
   ├─ routes
   │  ├─ menu.route.ts
   │  ├─ order.route.ts
   │  ├─ restaurant.route.ts
   │  └─ user.route.ts
   └─ utils
      ├─ cloudinary.ts
      ├─ generateToken.ts
      ├─ generateVerificationCode.ts
      └─ imageUpload.ts

```