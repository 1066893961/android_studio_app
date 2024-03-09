# android_studio_app
android各种毕设项目，您需要的我都有

# 具体项目演示视频，app运行效果录屏
# 哔哩哔哩直接搜索：   UID:632431488    
# （搜索框中一定要输入 uid+uid号）

闲来无事，整理了一些对之前帮同学做过的小项目，希望能 帮到正在紧张准备毕设项目的你！项目挺多总有一个适合你！ 如果有问题需要帮忙 我也可以帮忙指导指导。

Android毕设项目 （需要源码直接私信我）
幼儿园管理App
社区管理App
掌上家校App
蛋糕外卖App
点餐App
无接触送餐App
儿童成长记录App
手机银行App
公交站点查询App（基于高德地图API）
学生信息管理App
班费管理App
智能储物柜App
Android职业能力跟踪App
心理健康测试App
心理健康管理App
视频播放App
校园新闻App
少儿编程课程管理App
商城App
记账App
花艺App
提示：以上项目均有源码，可以正常部署自己电脑运行，也可以定制开发各种app。
说明： 以下项目均使用Android studio开发，代码使用java语言，布局文件使用xml，后端接口部署在自己电脑或者阿里云上面，后端使用ssm框架开发。

类似京东商城app
首先是登录、注册，然后进入首页使用viewpager+fragment实现四个不同tab的切换，tab包括（商品列表、促销商品、购物车、我的）
	  @Override
    protected void initView(Bundle savedInstanceState) {
        List<TabLayoutInfo> list = new ArrayList<>();
        list.add(new TabLayoutInfo(R.drawable.homepage_tab_workbench, R.string.homepage, GlobalKeyContans.MAIN_HOMEPAGE_INDEX));
        list.add(new TabLayoutInfo(R.drawable.homepage_tab_garb_single, R.string.account, GlobalKeyContans.MAIN_SINGLE_INDEX));
        list.add(new TabLayoutInfo(R.drawable.homepage_tab_basic, R.string.forum, GlobalKeyContans.MAIN_FORUM));
        list.add(new TabLayoutInfo(R.drawable.homepage_tab_my, R.string.my, GlobalKeyContans.MAIN_MY_INDEX));
        mDynamicTabLayout.setTabList(list);
    }
![image](https://github.com/1066893961/android_studio_app/assets/9737090/55bf932e-1a0a-423b-9a53-0cd60cd25810)

类似头条校园资讯类app
登录 ：
![image](https://github.com/1066893961/android_studio_app/assets/9737090/d44593f2-a5b0-4529-9c2e-ff8cbd91d11e)


注册：
![image](https://github.com/1066893961/android_studio_app/assets/9737090/4f85780a-0e1f-44bc-a747-d2de6a4cad87)


还包括文章的详情、评论、收藏、个人信息的修改、收藏列表等等 资讯列表、文章内容不好截图 就不一一展示了

![image](https://github.com/1066893961/android_studio_app/assets/9737090/c114f8ee-e905-49d8-8fa3-d6e7172d591f)



# 各种毕设项目，需要源码的可以加我微信  18911450394   

