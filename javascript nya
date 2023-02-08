function displayTime(){
    var dateTime = new Date();
    var hrs = dateTime.getHours();
    var min = dateTime.getMinutes();
    var sec = dateTime.getSeconds();
    var session = document.getElementById('sesi')
    if(hrs >=12) {
        sesi.innerHTML = 'PM';
    }
    else {
        sesi.innerHTML = 'AM';
    }
    document.getElementById('jam').innerHTML = hrs;
    document.getElementById('menit').innerHTML = min;
    document.getElementById('detik').innerHTML = sec;
}
setInterval(displayTime, 10)
