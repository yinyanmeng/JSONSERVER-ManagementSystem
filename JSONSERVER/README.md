//获取所有用户信息
http://localhost:3000/users

//获取id为1的用户信息
http://localhost:3000/users/1

//获取公司的所有信息
http://localhost:3000/companies

//获取单个公司的信息
http://localhost:3000/companies/1

//获取所有公司id为3的用户
http://localhost:3000/companies/3/users

//根据公司名字获取信息
http://localhost:3000/companies?name=Apple

//根据多个名字获取公司信息
http://localhost:3000/companies?name=Apple&name=Applebbbb

//获取一页中只有两条数据
http://localhost:3000/companies?_page=1&_limit=2

//升序排序 asc升序 desc降序
http://localhost:3000/companies?_sort=id&_order=desc

//获取年龄32及以上的数据
http://localhost:3000/users?age_gte=32

//获取年龄在32到34之间的数据
http://localhost:3000/users?age_gte=32&age_lte=34

//根据搜索信息
http://localhost:3000/users?q=bbbb