����� �������� �� ����.
1) ������ �������� � ��������� ������
������:
python manage.py migrate - ��������
python manage.py runserver - �������� ������� http://127.0.0.1:8000/riddles/
(python manage.py createsuperuser - �������� ����� ������������)
http://127.0.0.1:8000/admin/ - root\root\root@mail.ru
----------------------
index: Index ���������� ������� render. �� ���� ��� �������� HttpRequest, ��������������� ������� � ��� ����������, � ���������� HttpResponse � ������������� html.
detail: Detail ������ ����������� �� �� �����, �� ������ ������� get_object_or_404 ���������� HttpResponse404, ���� ������ ������ �� ��� ������.
answer: Answer ���� ��������������� ������� (� ���������� 404, ���� ��� �� �������) � ��������� ������������ ������.
---------------------