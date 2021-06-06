# ĐỒ ÁN FRONT-END BASIC: STARBUCKS

Đồ án Starbucs là một trong đồ án tốt nghiệp khóa học FEB19 Kmin... 

## Tính năng nổi bật

+ Phiên bản ReactJS mới nhất tính đến 12/10/2019 (GMT+7) - ver 16.10.2
+ Responsive bắt mắt
+ Thuật toán Search Bar đột phá
+ Chia folders SASS và sử dụng SASS
+ Thiết kế cố gắng tận dụng material-ui
+ Validation
+ Có demo test bằng Jest/Enzyme và react/tesing
+ Firebase Firestore
+ Sử dụng API với data chất lượng - độc - lạ từ TMDB
+ API chạy được và trả về nhiều states
+ Chi tiết đặt vé - thông tin phòng vé được thiết kế bắt mắt
+ Tích hợp API Facebook dễ dàng đăng nhập
+ Update thường xuyên
+ Cải tiến và tối ưu hết mức để tăng SEO
+ Live support
+ Scroll to top

## Cấu trúc thư mục

```
starbucks
.
├── ISSUE_TEMPLATE.md
├── LICENSE.md
├── README.md
├── bower.json
├── gulpfile.js
├── jsconfig.json
├── package.json
├── documentation
│   ├── assets
│   │   ├── css
│   │   ├── img
│   │   │   └── faces
│   │   └── js
│   └── tutorial-components.html
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
        reportWebVitals.js
    ├── App.css
    ├── App.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── routes.js
    ├── assets
    │   ├── css
    │   │   └── material-dashboard-react.css
    │   ├── github
    │   │   ├── md-react.gif
    │   │   └── react.svg
    │   ├── img
    │   │   └── faces
    │   └── jss
    │       ├── material-dashboard-react
    │       │   ├── components
    │       │   ├── layouts
    │       │   └── views
    │       └── material-dashboard-react.js
    ├── components
    │   ├──  FixedPlugin
    │   │     └── FixedPlugin.js
    │   ├──  Banner
    │   │     └── index.jsx
    │   ├──  Cinema
    │   │     └── index.jsx
    │   ├──  Dropdown
    │   │     └── index.jsx
    │   ├── Card
    │   │   ├── Card.js
    │   │   ├── CardAvatar.js
    │   │   ├── CardBody.js
    │   │   ├── CardFooter.js
    │   │   ├── CardHeader.js
    │   │   └── CardIcon.js
    │   ├── CustomButtons
    │   │   └── Button.js
    │   ├── CustomInput
    │   │   └── CustomInput.js
    │   ├── Footer
    │   │   ├── index.jsx
    │   │   └── index.css
    │   ├── Header
    │   │   └── index.jsx
    │   ├── News
    │   │   └── index.jsx
    │   ├── Partner
    │   │   └── index.jsx
    │   ├── Footer
    │   │   └── Footer.js
    │   ├── Grid
    │   │   ├── GridContainer.js
    │   │   └── GridItem.js
    │   ├── Navbars
    │   │   ├── RTLNavbarLinks.js
    │   │   ├── AdminNavbarLinks.js
    │   │   └── Navbar.js
    │   ├── Popup
    │   │   ├── AddShowTime.jsx
    │   │   ├── CUMovie.jsx
    │   │   ├── CUUser.jsx
    │   │   └── DetailUser.jsx
    │   ├── SlickMovie
    │   │   ├── index.jsx
    │   │   ├── NextArrows.js
    │   │   └── PreArrows.js
    │   ├── Sidebar
    │   │   └── Sidebar.js
    │   ├── TixApp
    │   │   └── index.jsx
    │   └── Table
    │       └── Table.js
    │       └── MovieTable.js
    │       └── UserTable.js
    │  
    ├── layouts
    │   ├── Admin.js
    │   └── User.js
    ├── variables
    │   ├── charts.js
    │   └── general.js
    ├── views
    │    ├── User
    │    │   ├── Login
    │    │   ├── Signup
    │    │   ├── Detail
    │    │   ├── Information
    │    │   ├── Checkout
    │    │   └── Homepage
    │    └── Admin
    │        ├── MovieManager
    │        ├── ShowtimeManager
    │        └── UserManager
    └── redux
        ├──  Actions
        │    ├── index.js
        │    ├── MovieActions.js
        │    ├── MovieTheaterActions.js
        │    ├── TicketActions.js
        │    └── UserActions.js
        ├── Constants
        │    ├── MovieConstants.js
        │    ├── MovieTheaterConstants.js
        │    ├── TicketConstants.js
        │    ├── UserConstants.js
        │    └── TimeConstants.js
        ├── Reducers
        │    ├── MovieReducers.js
        │    ├── MovieTheaterReducers.js
        │    ├── TicketReducers.js
        │    ├── UserReducers.js
        │    └── credential.js
        ├── storeConfigs.js
        └── theme
             └── index.jsx
```

## Browser Support

Chrome, Firefox, IE, Microsoft Edge, Safari

## Reference

+ Source: https://www.starbucks.vn/
+ http://w3schools.com/


## Code

```css
.little-box {
  box-sizing: border-box;
  width: 120px;
  padding-left: 20px;
  padding-right: 20px;
}
```

```html
<div id="container">
  <img src="lifesaver.jpg" alt="Lifesaver" />
  <p>Pellentesque habitant morbi tristique senectus...</p>
  <div class="clearfix"></div>
</div>
```