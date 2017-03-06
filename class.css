//获取
function getByClass(obj,sClass){
	if(obj.getElementsByClassname){
		return obj.getElementsByClassName;
	}else{
		var res =[];
		var aAll = obj.getElementsByTagName('*');
		for(var i =0;i<aAll.length;i++) {
			var re = new RegExp('\\b'+sClass+'\\b','g');
			if(re.test(aAll[i].className)){
				res.push(aAll[i]);
			}
		}
		return res;
	}
}
//判断
function hasClass(obj,sClass) {
	var re = new RegExp('\\b'+sClass+'\\b','g');
	if(re.test(obj.className)) {
		return true;
	}
	return false;
}
//添加
function addClass(obj,sClass) {
	if(obj.className){
		if(!hasClass(obj,sClass)){
			obj.className += ' '+sClass;
		}
	}else{
		obj.className = sClass;
	}
}
//删除
function removeClass(obj,sClass) {
	var re  = new RegExp('\\b'+sClass+'\\b','g');
								//删除sClass				去除首尾空格			将中间多个空格替换为一个空格
	obj.className = obj.className.replace(re,'').replace(/^\s+|\s+$/g,'').replace(/\s+/g,' ');
}
