# 5.使用 MySQL 数据库

 __ 阅读前后最好要了解一些 SQL 语言的知识。 __

而后，提醒一点：PHP 的 mysql 扩展现在已不建议使用，而且即将废弃。应该使用 mysqli 扩展对应的函数或类。

## 基本步骤 
### 连接到 MySQL 服务器
    
    // 一般使用面向对象的写法。mysqli 是 mysqli 扩展的类。
    $db = new mysqli('hostname','usename','password','database');
    

在连接数据库之后，通常还要进行连接时字符集设置，以避免连接过程中出现乱码： 
    
    $db->set_charset('utf8');   // `utf8` 是 MySQL 中常用的编码类型。
    

其中，`$db` 是一个包含连接资源(Resource)信息的对象。因为包含资源型的变量，因此对其进行序列化等操作是无效的。

另外，连接数据库的过程不是一帆风顺的。相关错误处理，请见底部参考资料中 PHP 官方手册。
	
### 选择接下来操作的数据库
	$db->select_db(db_name);

### 查询数据库
    
	$sql = "SELECT * FROM `dbname` WHERE `column`='value001' ";
	$result = $db->query($sql);
`   // $result 即得到的查询集，也是一个包含了查询资源的对象。
    // 并请注意：在下一步进行之前，最好检查 $result 是不是为假（FALSE）。当查询失败时（通常由于 sql语句出错、或 MySQL 连接丢失引起），query函数返回 FALSE。
    

### 检测查询结果
    
	$num_result = $result->num_rows;    // 本语句返回查询集的结果个数
	

### 关闭数据库连接
    
	$db->close();
	
## 参考资料
下面列出的是一些建议读者认真阅读的资料，这些资料对于加强对相关细节的认识和处理，具有很大的好处。

 * [PHP 官方文档 - mysqli](http://php.net/manual/zh/class.mysqli.php)

