ShellStudy
==========

shell���shell��̱ʼǣ�������¡�

##2. ���Ϊһ��Ŀ¼�µ�����jpgͼƬ�ļ�����ļ�����׺�������µ���ͼƬ��������ͬĿ¼�£�
for file in *.jpg; do cp "$file" "${file%.jpg}_small.jpg"; done
