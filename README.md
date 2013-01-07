MinifyX-for-Evolution
=====================
Component MinifyX for MODX Evolution

������� ���������
----------
- ������ ����� assets � ������ ������ �����
- ������� ������� MinifyX � ����� �� ����� **snippet.txt**

����������� ���������
----------
- ������� ������ MinifyX � ����� �� ����� **plugin.txt** � ��������� � ������� OnDocFormSave
- ������� ������ MinifyX � ����� �� ����� **module.txt**
- ������� ����� �������� MinifyX ��� ��������� CSS ������ � �������� blank � ����� ����������� text/css
- ������� ����� �������� MinifyX ��� ��������� JS �������� � �������� blank � ����� ����������� text/javascript
- � ���������� ������ �� ������� ������������ �������� �������� &CSSfile=CSS �����;textarea; &JSfile=JS �����;textarea; &CSSdoc=ID CSS ���������;int; &JSdoc=ID JS ���������;int;
- � ��������� ID JS ��������� � ID CSS ��������� ������� ID ����� ��������� ����������
- � ��������� JS ����� � CSS ����� ������� ������ ���� �� ����� ����� � ������ ������� ���������� �������. ���� ��������� ������ ������ ����, �� �� ������� ��������� �������
- ��������� ������� "����� ���������" � ��������� ������
- ����� ������� ������ �� �������������� � ����� �� ������� �����������. ����� ��������� ���������� ������������� � �������� ������ MinifyX � �����������.

����������� ��� ������� ���������
----------
������ �������� � ����������� **�� �������������**

	[!MinifyX? &CSSfile=`assets/templates/tpl/css/bootstrap.css,assets/js/prettify/prettify.css` &CSSdoc=`2` &JSfile=`assets/js/jquery-1.8.3.min.js,assets/templates/tpl/js/modernizr.custom.28468.js,assets/js/jquery.validate.js,assets/js/jquery.form.min.js,assets/js/prettify/prettify.js` &JSdoc=`3` &parse=`1`!]

��������� ��������
-------
- **CSSfile** ������ ������ � CSS �������, ������� ����� �������� � �������� ���� � �����
- **CSSdoc** ID ��������� � ������ ���������� � CSS �������
- **JSfile** ������ ������ � JavaScript �����, ������� ����� �������� � �������� ���� � �����
- **JSdoc** ID ��������� � ������ ���������� � JavaScript �����
- **parse** ������������ �� MODX ���� � ���������� ��������� � ������ ����������
- **cssFile** ��� CSS ����� �� ������. �� ��������� style.css
- **jsFile** ��� JS ����� �� ������. �� ��������� script.js
- **outFolder** � ����� ����� ��������� ������ ����. �� ��������� assets/cache/
- **API** ����� ������� ��������. �� ��������� ���������� API �������� � � ������ ��������� ���������� ���� ������ ������� ����������� � ������ head ������ ���-�����. ���� �� ����� API ������� (��� ��������� ���������� ������� ����� �������� ����� ���������), �� ��������� ����� ������ ������� ������ � ���� ������� array('js'=>'���� � ������� JS �������','css'=>'���� � �� ������� CSS �������'); � ������ ���� ����� ���� �� ������� ��� �����-�� ��� ������ �� ����������� �������, �� ���� ������� ������� ����� ����.

����������� ��� ����������� ���������
--------
- �������������� ������������ CSS ��� JS ����� ��� ��������� ��������� � CSS ������� � JS ����� ��������������
**�����!!!** ���� � ���� ���������� ������������ MODX ���� � �������� ���� ����� ������� �� ������ ����������, �� ���������� ����������� ������� � ��������� ��������������� �������, ����� ����� ��������������� ��� ������ �������� ���� MODX. �� ������ ����� � �� ����������. ����� ������ ��������� ���� �������� �� �������� MinifyX � ����������� ��� � ������� ��� src="[~id~]"
- ����������� ������� ������������ ������ ������ ��� ������ ������� ������

� ��������
---------
- � ������� ������->�������� ������� ������ ������� ����� ����������� � ���������� ����� ������. ���� �� ���������� ���������� ���������� � �������������� ������ ������ ��� ������������ ������
- ��� ����������� ������������ � �������� ���������� �������������� ��������� ����������� ������ JS � CSS ������. �� ��������� ��� /assets/cache/script.js � /assets/cache/style.css
	
TODO
--------
- � ��� ����� ��������� ��� ��� �������������� �������� ���������� �����
- ���� ���� ���������� � ��� ����� ��������� � ������� ����� ����������, �� ����� ������ return ������, � �� ������� �������� 
- ��������� ���� ����� � ��������� �������� � �� ������� ������������ � ������
- ������ ��������� � MinifyX.core.php
- ��������� ����� ���������� ���������� ������ ���� �� ������ ����������
- �����������, �.�. ����� ����� �������� ����� �������� ��� ������ ���������