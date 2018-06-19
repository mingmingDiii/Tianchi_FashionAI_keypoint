Fashion AI keypoint 4.27%

stage1 里面是输入整张图来获取外围点CUT图片的 \
stage2 里面是用CUT下来的图像训练 \

把除了测试集以外的所有图像都放在data/image_ori/Images中去，\
然后data_lib中分别生成S1和S2的tfrecord,然后分别在stage1和stage2中训练