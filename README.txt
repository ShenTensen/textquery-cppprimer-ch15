C++ Pirmer第5版第15章的TextQuery程序
代码来自infomit.con/title/0321714113，我让它直接运行起来，供人学习。

直接打开拿Visual Studio2019打开TextQuery.sln。

注意目录结构：
随便哪个目录/
    TextQuery.sln

    TextQuery/
        src/
            所有的.h，.cpp，.cc文件
        
        TextQuery.vcxproj
        TextQuery.vcxproj.filters
        TextQuery.vcxproj.user
    
 注意要在命令行下读取data目录下的文件，才可以查找，不这么做，虽然能运行，但也是查询不到。
