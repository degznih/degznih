javascript:(function(){
    for(let radio of document.querySelectorAll("[id='radioX']")) {
        radio.querySelectorAll('[type="radio"]')[4].checked = true
    }
})();
