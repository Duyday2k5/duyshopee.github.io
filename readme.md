*Reset css: normalize
code mau: https://shopee.vn/shop/234984535/search
Can I you (website biet thuoc tinh ho tro)

**CSS
1. :root  (ran mau) 
2. box-sizing: inherit; (the ke thua)
3. gg roboto font : dung font chu (ex)
4. 62.5% = 10px (1.6rem = 16px)
5. object-fit: contain (hien thi anh khong bi meo)
6. user-select: none (reset con tro chuot default)
7. transform: scale(0) --> scale(1) (dung keyframes -- animation (thu phong))
    + transform-origin: top right (di chuyen animation tu goc tren ben phai)
8. Create arrow(tao mui ten)
    + border-style: solid;
      border-width: 20px 28px;
      position: absolute;
      border-color: transparent transparent var(--white-color) transparent;
      outline: none; (loai bo vien dam khi nhay vao input)
0. will-change: opacity, transform (ex) (tao muot ma cho animation, thuoc tinh se thay doi)
10. :focus (use for border)
11. filter: brightness(80%) (giam do sang con 80%)
12. flex:
    + justify-content: flex-end|flex-start (move about left or right)
13. padding-top: 100%; (lam hinh vuong va hien thi anh)
14. display: -webkit-box;
    -webkit-box-orient: vertical; (theo huong nao: doc) 
    -webkit-line-clamp: 2; (so dong muon hien thi)

    text-overflow: ellipsis; (vd: giup tao dau 3 cham trong 1 line)
15. white-space: nowrap (de chu khong bi xuong dong)
16. **NEWs CSS: .product__item-heading (Ctrl + F)
17. text-decoration: line-througt (gach naang text)
18. align-item: base-line (can chan trang)
19. max-width: 100%;
    overflow-x: auto; (tao thanh keo len xuong)
    flex-shrink: 0; (tu dong cho nam ngang)
20. :nth-of-type(2n) (select bl2 roi bl2) (con bo n la chi select duoc 1 block)
21. .mobile__category-list::-webkit-scrollbar {
    display: none;
    }  (an di thanh truot khi dung overflow-x)#   d u y s h o p e e . g i t h u b . i o  
 