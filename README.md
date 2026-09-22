
            #region Задания по группам.

            #region Арифметические операторы.

            //1.Вычислите результат выражения int x = 17 / 5; int y = 17 % 5;
            //int x = 17 / 5; 
            //int y = 17 % 5;
            //Console.WriteLine($"Ответ: x = {x}; y = {y}");
<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/30e81fd8-500e-42e4-a962-d0fabe80c6e9" />

            //2.Каково значение res после выполнения int a = 5; int res = ++a * 2;?
            //int a = 5;
            //int res = ++a * 2;
            //Console.WriteLine($"Ответ: {res}");
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/7c945df9-7307-4300-bbb1-48502b427484" />

            //3.Каково значение res после выполнения int a = 5; int res = a++ * 2;?
            //int a = 5;
            //int res = a++ * 2;
            //Console.WriteLine($"Ответ: {res}");
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/1796391e-3758-4f0d-9af3-f96b99f5da0b" />

            //4.Чему равен результат 7 / 2 и 7.0 / 2?
            //int a = 7 / 2;
            //double b = 7.0 / 2;
            //Console.WriteLine($"Ответ: {a}; {b}");
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/51b2f06c-36d9-4c61-a2f5-4ed785529e0e" />

            //5.Каков результат выражения -15 % 4 в C#?
            //int a = -15 % 4;
            //Console.WriteLine($"Ответ: {a}");
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/b43ad1f1-e308-4c19-8b16-9b3fa252741a" />

            //6.Что выведет выражение int x = 10; x = x++ + ++x;?
            //int x = 10;
            //x = x++ + ++x;
            //Console.WriteLine($"Ответ: {x}");
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/0d1d5914-07a0-43e2-b982-37fac34c9263" />

            //7.Что произойдет при выполнении int max = int.MaxValue; int res = checked(max + 1);
            //int max = int.MaxValue;
            //int res = checked(max + 1);
            //Console.WriteLine(res);
<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/737461ce-812e-4e55-adf5-87686e5ff91a" />

            //8.Что произойдет при int max = int.MaxValue; int res = unchecked(max + 1);
            //int max = int.MaxValue;
            //int res = unchecked(max + 1);
            //Console.WriteLine($"Ответ: {res}");
<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/1d12822f-c3af-4bbe-8603-b8401fbe0143" />

            //9.Чему равен результат деления 1.0 / 0.0 и 0.0 / 0.0? 
            //double a = 1.0 / 0.0;
            //double b = 0.0 / 0.0;
            //Console.WriteLine($"Ответ: {a}; {b}");

<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/d3a88b86-8625-4322-9482-687f862727f6" />

            //10.Вычислите: int a = 8; int b = 3; int c = a - b * 2 + a / b;
            //int a = 8;
            //int b = 3;
            //int c = a - b * 2 + a / b;
            //Console.WriteLine($"Ответ: {c}");
<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/a4530d1e-44e9-406c-839c-c51af1c46adc" />

            #endregion

            #region Операторы сравнения и равенства.

            //1. Каков результат 5 > 3 и 5 >= 5?
            //bool a = 5 > 3;
            //bool b = 5 >= 5;
            //Console.WriteLine($"Ответ: {a}; {b}");

<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/4a6604d1-bbfc-41f4-b547-50439c9467cb" />

            //2.Чему равно "hello" == "hello" в C# и почему?
            //bool a = "hello" == "hello";
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/9783a6a4-85ce-4252-8c47-2fc004d44b4c" />

            //3.Чему равно выражение double.NaN == double.NaN?
            //bool a = double.NaN == double.NaN;
            //Console.WriteLine("Ответ: " + a);             //(Nan не равен ничему, даже самому себе).
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/8bb76dc0-4e3c-4b98-920a-b1522349870b" />

            //4.Каков результат выражения object a = new int[] { 1 }; object b = new int[] { 1 }; bool r = a == b;
            //object a = new int[] { 1 };
            //object b = new int[] { 1 };
            //bool r = a == b;
            //Console.WriteLine("Ответ: " + r);              //(сравниваются ссылки на два разных объекта в куче).
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/c3ba14d6-7200-4c06-840b-45ffb181a0f2" />

            //5. Чему равно 10 != 10.0? 
            //bool a = 10 != 10.0;
            //Console.WriteLine($"Ответ: {a}");               //(целое число 10 неявно приводится к 10.0, значения равны).
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/3cf3c077-0b60-43f7-84aa-3a739a5bf912" />

            //6.Что вернет null == null?
            //bool a = null == null;
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/db0606ee-1ef2-4512-bbf1-838d8bc833fb" />y

            //7.Каков результат выражения (3 < 5) == (10 >= 20)?
            //bool a = (3 < 5) == (10 >= 20);
            //Console.WriteLine("Ответ: " + a);

<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/9d439019-ae7e-484d-9eea-8ae53fa1b2c5" />

            //8.Вычислите bool res = 4 <= 4 && 5 > 2;
            //bool res = 4 <= 4 && 5 > 2;
            //Console.WriteLine("Ответ: " + res);
<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/98d1fe67-0fd9-4c78-8ee4-a4e8e686eb18" />

            //9.Что вернет выражение char c = 'b'; bool res = c > 'a';?
            //char c = 'b';
            //bool res = c > 'a';
            //Console.WriteLine("Ответ: " + res);
<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/ea5a8a1c-1846-40a1-bc0f-ae739ac71abb" />

            //10.Сравните результат bool r = -0.0 == 0.0;
            //bool r = -0.0 == 0.0;
            //Console.WriteLine("ответ: " + r);
<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/e1fbbbe9-4488-472d-8cd1-44fa3e50cff5" />

            #endregion

            #region Логические операторы.

            //1.Вычислите: !true || false && true.
            //bool a = !true || false && true;
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/9d5e1ce2-dec8-4cd6-ade7-085cf8e6508e" />

            //2.Будет ли вызван метод Foo() в false && Foo?
            //Console.WriteLine("Метод не будет вызван благодаря короткому замыканию &&");
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/22e122cd-23e3-42a7-827f-dbaf61fdcb1b" />

            //3.Будет ли вызван метод Foo() в false & Foo()?
            //Console.WriteLine("Метод будет вызван благодаря строгому логическому &, который вычисляет оба операнда");
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/d16965b3-840e-4748-94ce-9645cce34e52" />

            //4.Вычислите результат: true ^ false ^ true.
            //bool a = true ^ false ^ true;
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/d3863ebe-5844-455b-929e-6bda03d89b9d" />

            //5.Что вернет выражение !(5 > 2 || 3 < 1)?
            //bool a = !(5 > 2 || 3 < 1);
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/9601ef4b-f2f5-439c-a255-fcf220ab3343" />

            //6.Дано: bool a = true, b = false;. Чему равно a && !b || b && !a?
            //bool a = true, b = false;
            //Console.WriteLine($"Ответ: {a && !b || b && !a}");
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/50dd19e3-9039-4027-ae1a-56ad8e6fc491" />

            //7.Каков результат true || (x / 0 == 1) при любом целом x?
            //int x = 1;
            //bool a = true || (x / 0 == 1);
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/7fd4728e-d279-4839-a144-a63c9a57f614" />

            //8. Каков результат false & (10 / 0 == 1)?
            //int a1 = 10;
            //bool a = false & (a1 / 0 == 1);
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/43626dfa-41d5-4a6e-9437-8e5ca5f4e736" />

            //9.Чему эквивалентно выражение !(A && B) по закону де Моргана?
            //Console.WriteLine("Ответ: !A || !B");  //означает, что результат ложен только тогда, когда оба операнда A и B истинны одновременно
<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/3efbab76-7cb0-45a7-8c09-80668f31b6a0" />

            //10.Чему эквивалентно выражение !(A || B) по закону де Моргана?
            /*Console.WriteLine("Ответ: !A && !B"); */   //отрицание «А или B» истинно только в том случае, когда одновременно ложны и «не A», и «не B».
<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/69ccea99-d7fe-4257-b1e0-8ce02ee5fd7b" />

            #endregion

            #region Побитовые операторы и сдвиги.

            //1.Чему равен результат 5 & 3 в двоичном и десятичном виде?
            //int a = 5 & 3;
            //Console.WriteLine("Ответ: " + a);  //0101 & 0011 = 0001.
<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/dd9b46e4-867e-41b9-a923-c4e23be0e012" />

            //2.Чему равен результат 5 | 3?
            //int a = 5 | 3;
            //Console.WriteLine("Ответ: " + a);    //0101 | 0011 = 0111.
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/064419a8-a250-456f-8e78-587d6403e001" />

            //3.Чему равен результат 5 ^ 3?
            //int a = 5 ^ 3;
            //Console.WriteLine("Ответ: " + a);      //0101 ^ 0011 = 0110.
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/1bf807c6-dde7-4363-94d4-b50935d04a74" />

            //4.Вычислите ~0 для типа int.
            //int a = ~0;
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/475a8795-f45c-4804-9f3a-03f6dbc1e700" />

            //5.Чему равно 1 << 4?
            //int a = 1 << 4;
            //Console.WriteLine("ответ: " +  a);
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/994e6b4a-4f62-48ea-b074-8a6fafaf65aa" />

            //6.Чему равно 40 >> 2?
            //int a = 40 >> 2;
            //Console.WriteLine("Ответ: " + a);
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/58934349-14ff-4a5e-9a22-c8598ef5c3cd" />

            //7.Как с помощью побитовой операции проверить, установлен ли третий бит числа n (маска 2 * 2 * 2 * 2 = 8)?

            //8.Как с помощью побитовой операции установить 2-й бит числа n в 1?

            //9. Как сбросить (установить в 0) 4-й бит числа n?

            //10.Каков результат выражения (-16) >> 2 для int?
            //int a = (-16) >> 2;
            //Console.WriteLine("Ответ: " + a);

<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/8240f1be-1063-44b7-9d2e-889f7fb178cd" />

            #endregion

            #region Операторы присваивания.

            //1.Что делает оператор x + = 5?
            //Console.WriteLine("Ответ: Эквивалентен x = x + 5");
            //int x = 3;
            //int x1 = x + 5;
            //Console.WriteLine($"Пример: {x1} (int x = 3; int x1 = x + 5;)");

<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/39811107-1e89-47ea-a5cd-99f9732ef449" />

            //2.Каково значение a после выполнения: int a = 10; a *= 2 + 3;?
            //int a = 10;
            //a *= 2 + 3;
            //Console.WriteLine("Ответ: " + a); //(правая часть вычисляется полностью перед умножением: a = a * (2 + 3)).

<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/c96a0ff3-3b30-4b94-acfd-fc733f5536bd" />

            //3.Чему равен x после int x = 12; x >>= 2;?
            //int x = 12;
            //x >>= 2;
            //Console.WriteLine("Ответ: " + x); //12 / 4 = 3.
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/2bb7c5f0-0f64-434b-a3b1-0abd941dbf4c" />

            //4.Что делает оператор x ??= y?
            //Console.WriteLine("Ответ: Присваивает переменной x значение y только в том случае, если x == null.");
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/b429ba1b-c4fa-48d8-947c-ce35b45ba667" />

            //5.Чему будет равна строка str после: string str = null; str ??= "default"; str ??= "custom";
            //Console.WriteLine("Ответ: default");
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/f8896450-fc73-4b22-8aa3-cb31c46b1e91" />

            //6.Допустимо ли выражение byte b = 1; b += 2; без явного приведения?
            //byte b = 1;
            //b = (byte)(b + 2);
            //Console.WriteLine("Ответ: " + b);
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/d771d9af-96a7-48cf-94c1-5fccfd676c23" />

            //7.Чему равно значение c после int a = 5, b = 10, c = 0; c = a = b;
            //int a = 5, b = 10, c = 0; c = a = b;   //присваивание ассоциативно справа налево.
            //Console.WriteLine("Ответ: " + c);
<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/7fa74918-ee29-4a8a-82cb-3034822fadcf" />

            //8.Каково значение mask после: int mask = 1; mask <<= 3; mask |= 2;?
            //int mask = 1;
            //mask <<= 3;
            //mask |= 2;
            //Console.WriteLine("ответ: " + mask);

<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/97cb64d5-ab0b-40cf-8945-3805412adcf5" />

            //9.Чему равно x после int x = 15; x %= 4;?
            //int x = 15; 
            //x %= 4;
            //Console.WriteLine("Ответ: " + x);
<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/72a5c737-235b-4d35-8d03-e8a77e4228d7" />

            //10.Чему равно x после int x = 7; x ^= 7;?
            //int x = 7;
            //x ^= 7;
            //Console.WriteLine("Ответ: " + x);
<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/92639fb6-bbd9-43f8-bb25-024d0b908f8c" />

            #endregion

            #region Тернарный и null-операторы.

            //1.Вычислите int score = 75; string res = score >= 60 ? "Pass" : "Fail";
            //int score = 75; 
            //string res = score >= 60 ? "Pass" : "Fail";
            //Console.WriteLine("ответ: " + res);
<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/0eeded6b-13de-4d6c-be35-bccb11ae518c" />

            //2.Чему равно int x = 5; int y = (x > 10) ? 100 : (x > 2) ? 50 : 0;?
            //int x = 5; 
            //int y = (x > 10) ? 100 : (x > 2) ? 50 : 0;
            //Console.WriteLine("Ответ: " + y);
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/31e1c081-85fd-4d07-b5c6-fc6458eaa4ca" />

            //3. Какой тип имеет результат выражения true ? 10 : 15.5?
            //double a = true ? 10 : 15.5;
            //Console.WriteLine("Ответ: double");
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/cd84ed55-622f-4023-9a78-7776df86ab2f" />

            //4.Что выведет выражение string s = null; Console.WriteLine(s?.Length);?
            //string s = null; 
            //Console.WriteLine(s?.Length);
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/5656cc9e-8bbc-4caf-9f41-8b8ec0ba0ebc" />

            //5.Какой тип имеет результат выражения s?.Length для string s?
            //Console.WriteLine("ответ: int?");
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/59d92775-dd28-4118-b1e0-8d94125cb886" />

            //6.Вычислите: string name = null; string res = name ?? "Anonymous";
            //string name = null;
            //string res = name ?? "Anonymous";
            //Console.WriteLine("Ответ: " + res);
<img width="1920" height="1200" alt="№6" src="https://github.com/user-attachments/assets/7fb54e4c-be4a-440a-b29c-c72948f1554f" />

            //7.Вычислите: string a = null, b = "User", c = "Admin"; string res = a ?? b ?? c;.
            //string a = null, b = "User", c = "Admin"; 
            //string res = a ?? b ?? c;
            //Console.WriteLine("Ответ: " + res);
<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/0d965b1e-bfcd-4e36-ac45-0a1ca8892a17" />

            //8. Что вернет выражение false ? (10 / 0) : 42?
            //int a1 = 10;
            //int a = false ? (a1 / 0) : 42;
            //Console.WriteLine("Ответ: " + a); //второй операнд не вычисляется из-за ложного условия.
<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/9d5c0858-4e02-4a5c-81e8-1bdb10b58dc3" />

            //9.Скомпилируется ли код var x = condition ? 10 : "text";?
            //var x = condition 10 : "text";
            //Console.WriteLine("ответ: Нет");
<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/4b49bd80-11c6-45bc-89c9-52c64d46d751" />

            //10.чему равно int? count = null; int res = count?.GetHashCode() ?? -1;
            //int? count = null;
            //int res = count?.GetHashCode() ?? -1;
            //Console.WriteLine($"ответ: {res}");
<img width="1920" height="1200" alt="№10" src="https://github.com/user-attachments/assets/8387143d-3603-4cc8-80e1-256dfa2d9bff" />
           
            #endregion

            #region Операторы типов и приведения.

            //1.Что вернет выражение object obj = "Hello"; bool check = obj is string;
            //object obj = "Hello"; 
            //bool check = obj is string;
            //Console.WriteLine("Ответ: " + check);
<img width="1920" height="1200" alt="№1" src="https://github.com/user-attachments/assets/2a74ce66-44a7-47e5-af9b-de7af96d075c" />

            //2.Что вернет object obj = 123; string s = obj as string;?
            //object obj = 123; 
            //string s = obj as string;
            //Console.WriteLine("ответ: " + s);
<img width="1920" height="1200" alt="№2" src="https://github.com/user-attachments/assets/1e00bc31-964c-4227-b145-b0c6bedbf6df" />

            //3. Что произойдет при явном приведении object obj = 123; string s = (string)obj;?
            //object obj = 123; 
            //string s = (string)obj;
            //Console.WriteLine(s);
<img width="1920" height="1200" alt="№3" src="https://github.com/user-attachments/assets/7972d65b-cb7f-444e-b2a0-942711b0f753" />

            //4.Что вернет typeof(int) == typeof(Int32)?
            //object a = typeof(int) == typeof(Int32);
            //Console.WriteLine(a);
<img width="1920" height="1200" alt="№4" src="https://github.com/user-attachments/assets/089f3c26-316d-433e-b5b6-cc88020e5e26" />

            //5.Чему равен результат sizeof(long) в байтах?
            //Console.WriteLine($"ответ: {sizeof(long)}");
<img width="1920" height="1200" alt="№5" src="https://github.com/user-attachments/assets/d9d7f00a-98a7-4dde-8285-5219992a271b" />

            //6.Что вернет null is string?

            //7.Что вернет выражение object x = null; bool b = x is null;?
            //object x = null; 
            //bool b = x is null;
            //Console.WriteLine(b);
<img width="1920" height="1200" alt="№7" src="https://github.com/user-attachments/assets/8c60473b-cc79-4802-93d8-e354d3d2242a" />

            //8.Каков результат (int)3.99? 
            //Console.WriteLine((int)3.99);
<img width="1920" height="1200" alt="№8" src="https://github.com/user-attachments/assets/09b2b34c-1183-441e-a8ec-5d1312d944b8" />

            //9.Каков результат pattern matching: object o = 42; if (o is int val && val > 40) { ... }
            //object o = 42;
            //if (o is int val && val > 40) { };
            //Console.WriteLine(o);
<img width="1920" height="1200" alt="№9" src="https://github.com/user-attachments/assets/ebbfe75a-e9d1-41c5-bdb6-60fb3d2fc6a5" />
            
            //10.Что вернет выражение default(int) и default(string)?
            //Console.WriteLine(default(int));
            //Console.WriteLine(default(string));

            #endregion

            #region 35 сложносоставных заданий на логические выражения.

            //bool a = (5 > 3) && !(10 <= 2) || (4 == 5); Console.WriteLine(a); 
            //1. (5 > 3) &&(И) !(НЕ)(10 <= 2) ||(ИЛИ) (4 == 5)
            //(true && true) || false

            //bool a = !(true && false) ^ (true || false && false); Console.WriteLine(a); 
            //2. !(НЕ)(true && false) ^(лог.ИЛИ) (true || false && false)
            //true (^ возвращает true, только если операнды разные) true

            //bool a = (10 & 6) == 2 && (10 | 6) == 14; Console.WriteLine(a); 
            //3. (10 & 6) == 2 && (10 | 6) == 14
            //2 (0010) -> true && 14 (1110) -> true

            //bool a = (15 >> 1 == 7) && (7 << 2 == 28); Console.WriteLine(a);
            //4.

            //bool a = (8 > 5) && (3 + 2 * 4 == 11) && !(false || !true); Console.WriteLine(a);
            //5.

            //bool a = (true || false) && (false || true) ^ (true && !false); Console.WriteLine(a);
            //6.

            bool a = (100 / 10 == 10) && (100 % 30 == 10) && !(5 - 5 != 0); Console.WriteLine(a);
            //7.
            #endregion
            #endregion
