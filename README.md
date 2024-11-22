# vkplay-autoclick
вкплей-автокликер. скрипт нажимает много раз на голосование там, где можно голосовать много раз

## инструкция
1. открыть в новой вкладке канал с голосованием
2. обязательно поставить 1 бал и проголосовать один раз (окно голосования не закрывать)
3. открыть консоль ctrl+shift+j, вставить код(ниже), и нажать Enter

## код
```js
setInterval(() => {
    document.querySelector('.ButtonAlert_root_gyv7d').click();
    setTimeout(() => document.querySelector('.ConfirmPopup_confirm_Fzaao').click(), 500)
}, 600)
```

## автокликер на сундучок
setInterval(() => {
    let btn = document.querySelector('.PointActions_buttonBonus_F37Ur');
    if (btn) {
        btn.click()
    }
}, 1000);
