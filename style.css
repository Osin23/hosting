let team1 = document.querySelector('.team1')
let team2 = document.querySelector('.team2')
let team3 = document.querySelector('.team3')
let height = Math.max(parseInt(getComputedStyle(team1).getPropertyValue('height')), parseInt(getComputedStyle(team2).getPropertyValue('height')), parseInt(getComputedStyle(team3).getPropertyValue('height')))
team1.style.height = `${height}px`
team2.style.height = `${height}px`
team3.style.height = `${height}px`

function scrollDown() {
    window.scrollTo({top: window.innerHeight, behavior: 'smooth' });
}

let button = document.querySelector('.arrow-next')
button.addEventListener('click', scrollDown)

// Код, который нужно исправить
let item_name_objects = document.querySelectorAll('.merch-item-name')
let item_names = ['Тарелка', 'Кружка' , 'Ракета', 'Марсоход']
let description = ['Тарелка с принтом Марса. Доступна в красном и белом цветах' , 'Кружка с принтом Марса. Доступа в красном и белом цветах' , 'Масштабная модель одной из ракет Galaxy' , 'Масштабная модель масохода (мы покупаем их у NASA)']
let price = [ 1000,
1000,
2500,
5000 ]
let desc_name = document.querySelectorAll('.merch-item-descr')
let price_name = document.querySelectorAll('.merch-item-price')
for (let i = 0; i < item_names.length; i += 1) {
    item_name_objects[i].innerHTML = item_names[i]
    desc_name[i].innerHTML = description[i]
    price_name[i].innerHTML = price[i]

}

let btn_cards = document.querySelectorAll('.add-to-cart-btn')
let number_items = document.querySelector('.cart-amount')

for (let i = 0; i < btn_cards.length; i += 1){
    btn_cards[i].addEventListener('click' , function(){
        number_items.innerHTML = +number_items.innerHTML + 1
        })
}
