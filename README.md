# testForDima
Тест-репозиторий для гита

## Конфликт и его разрешение:
Есть 2 ветки:
`main` и `branh_to_edit`
Изменения произошли следующие:

`main`:

    code_to_edit:
         - return a + b
         + return a - b
    main:
        - first/second = 5/12
        + first/second = 10/112
        - print (..'+'..)
        + print (..'-'..)
`branh_to_edit`:

		code_to_edit:
			- return a + b
			+ return (a + b) * (a - b)
Задача: из ветки `branh_to_edit` выполнить `git pull origin main`, решить конфликт и залить коммит с решением конфликта
Заранее выполнить:

	git config pull.rebase true
