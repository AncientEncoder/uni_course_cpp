# Rules

1. Версия `C++`, которую мы будем использовать - `C++ 17`. Компилироваться ваши программы будут с помощью компилятора `clang` с флагом `-Werror`, это значит что все предупреждения компилятора будут считаться ошибками.
1. У нас с вами практикум по `C++`, поэтому использовать голый синтаксис `C` без крайней необходимости запрещено. Подробнее рассмотрено в секции [`C` vs `C++`](c_vs_cpp.md).
1. Использовать сторонние библиотеки также запрещено. Пользуйтесь теми инструментами, которые дает вам язык.
1. Чтобы упростить вам жизнь и избежать кучу головной боли, использовать `template` без крайней нужды запрещено.
1. По правилам хорошего тона, когда много людей работают над одним репозиторием, используется `linter` для контроля форматирования текста,
   чтобы весь код выглядел единообразно и всем его было удобно читать. В нашем случае, мы будем использовать `clang-format`. Подробнее описано в секции [`Workflow`](workflow.md).
