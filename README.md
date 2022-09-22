//FORM SUB
<!>
let formdom =document.queerrySelector("#userForm")
formDOM.addeventListener('submit', formSubmit)

function formSubmit(){
    event.preventDefault() //default işlemi engelledik...
    consolo.log("islem gerçeklesti")
}
