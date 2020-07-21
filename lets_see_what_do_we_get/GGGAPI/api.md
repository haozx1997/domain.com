添加班级
http://goodgoodlaugh.com:8080/GGG/TheClass/save
{"classId":"103","major":"软件工程"}
{"classId":"103","major":"软件工程","headTeacher":"常博豪"}

查找班级

http://goodgoodlaugh.com:8080/GGG/TheClass/getClassByClassId?classId=103

查看所有班级
http://goodgoodlaugh.com:8080/GGG/TheClass/getAll

更新班级
http://goodgoodlaugh.com:8080/GGG/TheClass/update
{"classId":"103","major":"软件工程"}
{"classId":"103","major":"软件工程","headTeacher":"常博豪"}



添加教室
http://goodgoodlaugh.com:8080/GGG/Classroom/save
{"classroomId":"hzxh", "size":50}


查看所有教室
http://goodgoodlaugh.com:8080/GGG/Classroom/getAll

查看所有可用教室
http://goodgoodlaugh.com:8080/GGG/Classroom/getAvailable

查看所有user教室
http://goodgoodlaugh.com:8080/GGG/Classroom/getByUser?user=hzx

使用教室
http://goodgoodlaugh.com:8080/GGG/Classroom/use?classroomId=hzx&user=hzx

取消使用
http://goodgoodlaugh.com:8080/GGG/Classroom/notUse?classroomId=hzx&user=hzx

