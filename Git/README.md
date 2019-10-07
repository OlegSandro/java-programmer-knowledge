# Git

Git – бесплатная распределенная система управления версиями с открытым исходным кодом. Позволяет отслеживать изменения в часто редактируемых текстовых файлах, в том числе в исходном коде программного обеспечения.  

Git помогает отслеживать изменения, предоставляя возможность откатываться до предыдущих версий. Также поддерживает одновременную работы нескольких человек над одним проектом, что влечет за собой активное использование Git'а в командной разработке ПО. Помимо всего прочего, Git в связке (например, с GitHub или BitBucket) способствует применению практики code review для проверки нового кода другими участниками команды.  

Поскольку каждая директория Git'а на каждом хосте является полноценной копией с полной историей изменений и возможностью их отслеживания, то с Git'ом предоставляется возможным работать даже независимо от подключения к сети, которая нужна в регулярных случаях только для чтения и записи в удаленнный репозиторий, а большинство других важных команд можно производить автономно.

Git работает по принципу слоистости. Изначальная версия изменений хранится как исходный код проекта целиком, а все последующие версии изменений хранят уже лишь те изменения, которые были произведены по отношению к предыдущей версии изменений.  

---

# Содержание

1. [Команды, заимствованные из различных операционных систем](#borrowed)
   * [Команды для навигации](#navigation)

---

# <a name="borrowed"></a> Команды, заимствованные из различных сред

В этом разделе представлены команды, которые часто используются в Git Bash в виду своей пользы и удобства, но при этом не являются командами Git. Они практичны и популярны, просты и незаменимы, поэтому о них стоит упомянуть именно с самого начала. Все они исторически зарекомендовали себя и являются командами терминала Unix-подобных систем либо командной строки Windows-подобных систем.

Условно разделим такие команды на 3 вида: команды навигации, команды управления файлами и команды отображения.

## <a name="navigation"></a> Команды для навигации

- `pwd` – показать абсолютный путь каталога, в котором находимся.