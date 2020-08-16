# demo-jquery
jQuery的基本设计思想和主要用法，就是"选择某个网页元素，然后对其进行某种操作"。
使用jQuery的第一步，往往就是将一个选择表达式，放进构造函数jQuery()（简写为$），然后得到被选中的元素。
<script>
$(function(){
	$('.addBook2Cart').click(function(){// 
		alert("hello");
	})
})
</script>