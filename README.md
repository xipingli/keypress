# keypress
data


$('#loginwindow input').bind('keypress', function (e) {  // '#loginwindow input'这是一个input的ID，此方法的功能是键盘上按钮的功能体现
       if(e.which == 13) {                               // 回车键的代码为‘13’，当e.which==13时，执行要执行的方法
   			login();
       }  
	});
