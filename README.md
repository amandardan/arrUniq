#多种数据类型数组去重

数组内的数据可以有多种数据类型，如基本型：`string,number,boolean,null,undefined`,复合类型`array,object,function`，平时的项目中都是构造一个很简单的json或者数组，因为工程师们都知道多数据类型数组去重没有现成的方法，也怕为之后的开发埋坑，虽然es6现在可以很简单的做到，但是毕竟没有成为正式的标准，不是所有浏览器都支持，所以这里写了一个基本的方法来进行处理方法有待改进，有更好的意见欢迎issue！

该方法直接写在来数组的prototype上，可以在数组后连接使用，如`arr.arrUniq()`;
