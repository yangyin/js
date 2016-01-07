# js
	option{
	
 main:main,	//最外层DIV，即可视区域
 
 div1:div1,	//与div2是兄弟关系，内容区域 高度与main一致
 
 div2:div2,	//与div1是兄弟关系，滚动条背景区域，高度与main一致
 
 div3:div3  //Div2的子级，滚动条
 
 size:控制滚动速度 和 滚动的方向 可选
 
 支持IE7+、FF、谷歌(IE6未测试)
 
 <div id=main>
 
  <div id=div1><div>
  
  <div id=div2>
  
   <div id=div3><div>
   
  <div>
  
 <div>
 
}
