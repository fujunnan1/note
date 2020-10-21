## 10.19
#### spring注解
1. @AutoWired:自动注解 

        @AutoWired(required=false)表示bean中找不到对应类型可以不注入
        当一个接口有多种实现,自动装配按类型（by type）获取bean不唯一无法判断,
        可通过@Primary、@Qualifier（按名称获取）消除歧义

        装载带有参数的构造方法类,在参数前加注解
2. @Bean

        @Component只能注解类
        @Bean可以注解到方法上
        


        