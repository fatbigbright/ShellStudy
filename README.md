ShellStudy
==========

shell���shell��̱ʼǣ�������¡�

######1. ���Ϊһ��Ŀ¼�µ�����jpgͼƬ�ļ�����ļ�����׺�������µ���ͼƬ��������ͬĿ¼�£�
for file in *.jpg; do cp "$file" "${file%.jpg}_suffix.jpg"; done
