# WinAPI

[project]:https://github.com/mazzy-ax/WinAPI
[license]:https://github.com/mazzy-ax/WinAPI/blob/master/LICENSE

[WinAPI][project] &ndash; это набор методов на языке X++ для классов WinAPI и WinAPIServer в [Microsoft Dynamics AX 2009](ax2009), [Microsoft Dynamics AX 2012](ax2012) и [Axapta 4.0](ax4).

## WinAPIServer

Методы класса WinAPIServer гарантировано выполняются на сервере. Дополнительно к стандартным методам это класса добавлены:

* createDirectory
* createDirectoryPath
* folderExists
* removeDirectory

Методы скопированы из клиентского WinAPI. В этих методах изменен модификатор server и расставлены разрешения FileIOPermission, InteropPermission.

## ChangeLog

* [CHANGELOG.md](CHANGELOG.md)
* <https://github.com/mazzy-ax/SysArgs/releases>

## Помощь проекту

Буду признателен за ваши замечания, предложения и советы по проекту как в разделе [Issues](https://github.com/mazzy-ax/WinAPI/issues), так и в виде письма на адрес <mazzy@mazzy.ru>

Мазуркин Сергей (mazzy)
