---
---

1. Hiding the shadow around button when you click "outline: 0 !important;"
 
    .btn.active.focus,
    .btn.active:focus,
    .btn.focus,
    .btn.focus:active,
    .btn:active:focus,
    .btn:focus {
        outline: 0 !important;
        outline-offset: 0  !important;
        -webkit-box-shadow: none !important;
        box-shadow: none  !important;
    }


2. Use "object-fit" property to adjust images are resized within their containers