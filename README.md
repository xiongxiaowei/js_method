# js_method
### 排序
```
<script type="text/javascript">
   	var aaa=[1,3,2,-7,6]
   	aaa.sort((a,b)=>a-b)
   	console.log(aaa)
</script>
```
### 字符串方法->split转化成数组
```
<script type="text/javascript">
      var a='apple,pear,orange'
      var b=a.split(',')
      console.log(b)
</script>
```
### 数组转化为字符串
```
  <script type="text/javascript">
      	var aaa=[1,3,2,-7,6]
   	    var a=aaa.join(',')
   	    console.log(a)
   </script>
```
### 字符串方法->indexOf想找出什么字符就找出什么，并能吧所有字符索引定位
```
 <script type="text/javascript">
      var a="sdafasfaklfahsjkjdhalfkajsflkasjdkajsfhakjsf"
      var pos=a.indexOf('a')
      var arr=[]
      while(pos>-1){
        console.log(a.charAt(pos),pos)
        arr.push(pos)
        pos=a.indexOf('a',pos+1)   
      }
      console.log(arr)
   </script>
```
### 数组遍历
```
        var aaa=[1,3,2,-7,6]
   	    aaa.forEach((i)=>console.log(i))
```
