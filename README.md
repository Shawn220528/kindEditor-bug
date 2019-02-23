# kindEditor-bug
1.kindeditor＆LT = 4.1.5文件上传漏洞<br/>
2.根本脚本语言自定义不同的上传地址，上传之前有必要验证文件upload_json.*的存在<br/>
# 解决方案
删除所有upload_json.* 和 file_manager_json.*文件
