# PyDealerClient

image recognition which sample live video and send result data to Dealer by net socket.

# release note
2022/11/2 v1.5.6
1. fix截图上传滞后16s.
2. log add gmSaveFinalResult and gmCount.
3. support samba folder to save snapshot images.
2022/10/22 v1.5.1
1. 不保存过程图片.
# if len(save_descjudge) > 0:
#     self.imageSaver.save(gmcode, int(pos.index), save_descjudge, save_scorejudge, predict_image_save, False)
imageSaver = ImageSaver(cfg.save_folder)  //可配置图片保存目录
2. 配置文件修改
	<save folder="./predict_images" autoUpload="0"/>

2022/10/5 v1.5.0
    only produce one full image and upload to FTP Server.

2022/8/16 v1.4.2
    init as baseline.

