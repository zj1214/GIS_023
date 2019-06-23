# mirrors
地信考研学校查询
故事逻辑：当准备报考学校时，一般会先对gis学校进行查询，查询方式可能是通过地区、报考科目等进行查询。同时也可以了解gis高校分布情况。最后当有了意向学校后，可以查询两点间的距离，所需时间，所需费用等，再对目标进行调整。（gis高校数据不全，仅作为系统数据，不作为报考参考）

页面右下角为鼠标点的位置和比例尺级别，左下角为图例，页面中的点为GIS高校，点击可以查看相关信息。
右上角为底图切换，可以通过缩略图进行查看，当有了想要切换的底图时，点击图片即可切换底图。
左上角三个按钮，第一个是省份查询，可以选择“学校”“省份”“城市”“学院”“专业”“初试科目”“参考书目”进行查询，也可输入关键字查询。在查询结果表格中，点击学校可以切换到其所在地，点击右上角的“X”即可结束查询。（下拉框和搜索按钮的图标显示不出来，但在本地运行没有问题，传到github中就无法显示，但不影响操作）
第二个按钮为区域统计，点击按钮会显示相关高校分布的echart图表，再点击此按钮即可关闭图表。
第三个按钮为异地恋分析，会跳转到另一html页面，在左上角的下拉框中选择学校，或者手动输入其他地区（例如家），点击“路径分析”，可以对数据进行查询，“查询路线”即可显示路线，点击空白处导航窗口消失，点击“清除按钮”清除图上的路线，点击“异地恋分析”会显示本系统给的建议。驾车导航与此类似。点击左上角返回上一页即可返回上一页即最初的html文件
