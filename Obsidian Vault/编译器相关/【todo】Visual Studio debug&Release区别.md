#编译器 
# 问题描述

在执行fore_gpu时，debug编译模式下可以运行，release可以生成项目，但运行报错。

``` cpp
# include <iostream>

```

![[Pasted image 20230605165929.png]]
![[Pasted image 20230605165949.png]]
![[Pasted image 20230605170022.png]]
![[Pasted image 20230605170038.png]]
![[Pasted image 20230605170209.png]]
E:\Projects\naoc-vc\fore_gpu\SpaceX\SpaceXFileParser.cpp(83,9): warning C4101: “mjd”: 未引用的局部变量：mjd、epoch变量未初始化，已修改
![[Pasted image 20230605170905.png]]

release生成时：
```
#error:  <hash_map> is deprecated and will be REMOVED. Please use <unordered_map>. You can define _SILENCE_STDEXT_HASH_DEPRECATION_WARNINGS to suppress this error.	SpaceX	C:\Program Files\Microsoft Visual Studio\2022\Professional\VC\Tools\MSVC\14.36.32532\include\hash_map	22	
```

