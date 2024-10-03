/ Заметки и приёмы по коду, которые можно переиспользовать в будущем

// Стили по умолчанию для псевдоэлементов after, before:

&::after(before) {
    content: '';
    position: absolute;
    width: 21px;
    height: 21px;
    top: 0;
    left: 0;
    background-image: url('');
    background-repeat: no-repeat;
}

// Стили для выравнивания элемента (position: absolute;) по центру элемента (position: relative;):

.&__icon {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
