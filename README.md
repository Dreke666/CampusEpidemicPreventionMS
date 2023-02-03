目前国内疫情趋于稳定，但是局部地区会有部分异常情况。如何全面的采集疫情信息，整理并展示出来，为疫情防控提供有力依据成为关键。这本身涉及到数据的采集、数据清洗、数据分析、数据可视化。直观的信息能够为政府部门、学校等单位提供防控有力的导向作用，能够为社会做出一定的贡献.

技术：
springboot

Vue2

Mysql8

开发工具：idea2020


###### **1.角色以及对应的权限**

**系统管理员**	

系统管理员具有最高权限，登录系统后可以管理后台数据库的信息，包括管理用户身份信息、用户的健康填报记录、用户的出校申请记录。

在通知栏处发布通知。

##### **辅导员**

辅导员有查看其辅导年级的学生身份信息权限。

查看其权限范围内的学生离校申请，学生离校申请以列表的形式呈现，分为已处理和未处理两类，对于未处理的申请可以进行同意或者撤回。

查看学生的健康填报记录，并可以根据学生的健康填报记录进行多条件查询，如是否有发烧症状、是否有体温异常等，查询结果以列表的形式呈现，可以导出为表格。

学生	学生拥有申请离校的权限，在系统中填写离校申请表单并进行提交。

学生拥有查看自己离校申请记录的权限，离校申请记录中可以看到辅导员的反馈，若被撤回可以修改后重新提交。

**其他教职工**

除辅导员之外的教职工拥有一般权限，即所有用户都可以执行的权限，包括修改自己的身份信息、进行健康填报以及查看通知栏处的通知和疫情地图。

目前国内疫情趋于稳定，但是局部地区会有部分异常情况。如何全面的采集疫情信息，整理并展示出来，为疫情防控提供有力依据成为关键。这本身涉及到数据的采集、数据清洗、数据分析、数据可视化。直观的信息能够为政府部门、学校等单位提供防控有力的导向作用，能够为社会做出一定的贡献.
