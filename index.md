



> 圆

* ctx.arc()       圆
* ctx.arcTo()     圆弧


> 线

* ctx.beginPath()     开始一个路径
* ctx.moveTo(x,y)     移动画笔到某点
* ctx.lineTo(x,y)     让路径中拥有(并不会直接绘出)一条到某点的线
* ctx.rect()          让路径中拥有(并不会直接绘出)一个矩形
* ctx.fill()          填充当前路径
* ctx.stroke()        描边当前路径
* ctx.closePath()     结束一个路径


>

* ctx.quadraticCurveTo(cp1x,cp1y,x,y)
二次贝塞尔
* ctx.bezierCurveTo(cp1x,cp1y,x,y)
三次贝塞尔


> 样式
从画布中清除矩形区域
画布的特点，绘制上的元素无法更改

* ctx.clearRect()

> 位移(挪动画布)
只保存画布状态(包含画笔)

* ctx.save()
* ctx.restore()








// HTMLCanvasElement
  // getContext('2d')
  // ctx.beginPath()
  // ctx.rect(x,y,width,height)
  // ctx.arc()
  // ctx.moveTo()
  // ctx.lineTo()
  // ctx.fillRect()
  // ctx.strokeRect()
  // ctx.fill()
  // ctx.stroke()
  // ctx.closePath();
  //
  // ctx.save();
  // ctx.restore();
  // ctx.translate();
  // ctx.rotate( (Math.PI/180)*30 );
  <!-- //
  // var LG = ctx.createLinearGradient(x1,x2,y1,y2);
  // LG.addColorStop(0.3,'#855363');
  // LG.addColorStop(0.5,'black');
  // var RG = ctx.createRadialGradient(x1,x2,r,y1,y2,r);
  // RG.addColorStop(0.3,'#855363');
  // RG.addColorStop(0.5,'black');
  //
  // ctx.save();
  // ctx.fillStyle = LG;
  // ctx.strokeStyle = RG;
  // ctx.restore();
  //
  // var IMAGE = new Image();
  // IMAGE.src = './bg.png';
  // $(IMAGE).on('load',function(){
  //   var TA = ctx.createPattern(IMAGE,'no-repeat');
  //   ctx.fillStyle = TA;
  //   ctx.fill();
  // })
  //
  //
  // ctx.lineWidth = 10;
  // ctx.lineJoin = 'inherit';
  // ctx.lineCap =  'round';
  // ctx.setLineDash([10,3]);
  // ctx.lineDashOffset = '-10';
  //
  // ctx.shadowOffsetx = 10;
  // ctx.shadowOffsetY = 10;
  // ctx.shadowBlur =  10;
  // ctx.shadowColor = 'red';
  //
  // ctx.font = '48px san_serif';
  // ctx.textAlign  = 'right';
  //
  // ctx.fillText("xdfadfa",0,0,300);
  // ctx.strokeText('xdadfa',0,0);
  //
  // var I = new Image();
  // I.src = './sprite.png';
  // I.onload = function(){
  //   ctx.drawImage(I,300,300);
  //   ctx.drawImage(I,300,300,200,200);
  //   ctx.drawImage(I,12,20,100,100,300,300,100,100); -->
