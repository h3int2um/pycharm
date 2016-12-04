# Cài đặt PyCharm trên Ubuntu 16.04

Tìm hiểu: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 04 tháng 12 năm 2016

## Tài liệu tham khảo

1. [HOW TO INSTALL PYCHARM IN UBUNTU 14.04 AND 16.04 - It's F.O.S.S.](https://itsfoss.com/install-pycharm-ubuntu/).

2. [How to Install The Latest PyCharm IDE in Ubuntu 16.04 via PPA - UbuntuHandbook](http://ubuntuhandbook.org/index.php/2016/07/latest-pycharm-ubuntu-16-04-ppa/).

## Tính năng của PyCharm IDE

* Syntax highlighting

* Auto-Indentation and code formatting

* Code completion

* Line and block commenting

* On-the-fly error highlighting

* Code snippets

* Code folding

* Easy code navigation and search

* Code analysis

* Configurable language injections

* Python refactoring

* Documentation

Để xem đầy đủ tính năng của `PyCharm` truy cập vào địa chỉ: [PYCHARM FEATURES](https://www.jetbrains.com/pycharm/features/index.html).

## Hướng dẫn cài đặt PyCharm trên Ubuntu 16.04

* Bước 1: `Add PyCharm PPA` vào source list.
		
		$ sudo add-apt-repository ppa:mystic-mirage/pycharm
		
	![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/install-pycharm-add-repository-ppa-ubuntu.png)
	
* Bước 2: Cập nhật lại `repository`:

		$ sudo apt-get update
		
	![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/install-pycharm-update-repository-ubuntu.png)
	
* Bước 3: Cài đặt `PyCharm`, có 2 phiên bản lựa chọn để cài đặt là `PyCharm Professional` và 
`PyCharm Community`.

	+ Cài đặt phiên bản `PyCharm Professional`:

			$ sudo apt install pycharm
			
		![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/install-pycharm-ubuntu.png)
		
	+ Cài đặt phiên bản `PyCharm Community`:
	
			$ sudo apt install pycharm-community
			
		![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/install-pycharm-community-ubuntu.png)
		
## Hướng dẫn gỡ bỏ PyCharm trên Ubuntu 16.04

* Bước 1: Gỡ bỏ `PyCharm` phụ thuộc vào phiên bản cài đặt.

	+ Gỡ bỏ phiên bản `PyCharm Professional`:
	
			$ sudo apt-get remove pycharm
			
		![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/remove-pycharm-ubuntu.png)
		
	+ Gỡ bỏ phiên bản `PyCharm Community`:
	
			$ sudo apt-get remove pycharm-community
		
		![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/remove-pycharm-community-ubuntu.png)
		
* Bước 2: Gỡ bỏ `PyCharm PPA` ra khỏi source list.

		$ sudo add-apt-repository --remove ppa:mystic-mirage/pycharm
		
	![](https://raw.githubusercontent.com/h3int2um/pycharm/master/images-pycharm/setup-pycharm/remove-pycharm-add-repository-ppa-ubuntu.png)
