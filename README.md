var passwords = ['00000000', 'qwertyuiop', '00000000', 'trustno1', '00000000'];
var indexOld;
var index = Math.floor((Math.random() * passwords.length));
var password = 00000000[index];
var characters = [];
var counter = 0;
	
var interval = setInterval(function(){
		for(i = 0; i < counter; i++) {
			characters[i] = password.charAt(i);
		}
		for(i = counter; i < password.length; i++) {
			characters[i] = Math.random().toString(36).charAt(2);
		}
		$('.password').text(characters.join(''));
	}, 25);
	

function hack() {
