# Cái này được viết ra để cho đứa chính cái đứa viết cái blog này hiểu nó đang làm gì

## Chứ thật ra có đọc file hay không mới là chuyện khác

## Một trang blog được code theo cấu trúc oop, do đứa viết blog là 1 java dev có ám ảnh về oop nên là phải chịu

blog-project/
├── index.html                          *Homepage with all sections*
├── indexBlog.html                      *Main blog pages*
├──recent/
|     |
|     ├── RecPost.html                  *Recent Posts (các bài nhỏ)*
|
├──myBlog/
|    ├──blog1.html
|    ├──blog2.html
|    ├──...
|
├── assets/
│   ├── css/
│   │   ├── vendor/
│   │   │   ├── main.css               *Template base*
│   │   │   └── fontawesome.min.css
│   │   ├── layout.css                 *Grid, spacing, responsive*
│   │   ├── sections/
│   │   │   ├── profile.css            *Profile section styles*
│   │   │   ├── background.css         *Background section styles*
│   │   │   ├── featured-blog.css      *Featured post styles*
│   │   │   └── recent-blog.css        *Recent posts grid styles*
│   │   └── components.css             *Buttons, cards, etc.*
│   ├── js/
│   │   ├── vendor/
│   │   │   ├── jquery.min.js
│   │   │   └── template.js
│   │   ├── models/
│   │   │   ├── Post.js                *Post entity*
│   │   │   ├── Profile.js             *Profile entity*
│   │   │   └── Section.js             *Section config*
│   │   ├── services/
│   │   │   ├── DataService.js         *Load all JSON data*
│   │   │   ├── PostService.js         *Post business logic*
│   │   │   └── SectionService.js      *Section management*
│   │   ├── renderers/
│   │   │   ├── ProfileRenderer.js     *Render profile section*
│   │   │   ├── BackgroundRenderer.js  *Render background section*
│   │   │   ├── FeaturedRenderer.js    *Render featured post*
│   │   │   ├── RecentRenderer.js      *Render recent posts grid*
│   │   │   └── PostDetailRenderer.js  *Render single post page*
│   │   ├── utils/
│   │   │   ├── dateFormatter.js       *Date utilities*
│   │   │   └── imageLoader.js         *Image handling*
│   │   ├── config.js                  *App configuration*
│   │   └── app.js                     *Main app controller*
│   └── images/
│       ├── profile/                   *Profile images*
│       ├── backgrounds/               *Section backgrounds*
│       └── posts/                     *Post thumbnails*
├── data/
│   ├── profile.json                   *Your profile info*
│   ├── background.json                *Background section content*
│   ├── posts.json                     *All blog posts*
│   └── sections-config.json           *Section layout configuration*
└── README.md

## Nó đơn giản là cấu trúc của cái blog này. Tránh đứa code mở lên và chửi cái đéo gì đây

## Nhưng đừng lo đứa mở cái này lên nó đã chửi cái quái gì rồi
