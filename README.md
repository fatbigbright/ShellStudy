ShellStudy
==========

shell���shell��̱ʼǣ�������¡�

######1. ���Ϊһ��Ŀ¼�µ�����jpgͼƬ�ļ�����ļ�����׺�������µ���ͼƬ��������ͬĿ¼�£�
for file in *.jpg; do cp "$file" "${file%.jpg}_suffix.jpg"; done

######2.
��ο���ɾ������Ŀ¼some_dir��
rm -rf some_dir , r stands for 'recursive', f stands for 'force'.
