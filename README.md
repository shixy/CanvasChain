CanvasChain
===========

简单的Canvas帮助类，使canvas支持类似于jquery的链式操作
支持CanvasRenderingContext2D所有的方法
属性请使用set方法来设置
此外还提供一些简单实用的画图工具方法

使用方法：
	var ctx = window.Canvas('canvasId');
	ctx.set('fillStyle','red')
	   .line(0,0,10,10)
	   .set({
			stokeStyle : '#000'
			lineWidth : 2
	   })
	   .arc(.......)


** 持续完善中..
enjoy it！