# CodeStyle.CSharp

## 命名样式

### 帕斯卡

```csharp
dotnet_naming_style.帕斯卡.required_prefix =
dotnet_naming_style.帕斯卡.required_suffix =
dotnet_naming_style.帕斯卡.word_separator =
dotnet_naming_style.帕斯卡.capitalization = pascal_case
```

### 以 I 开头帕斯卡

```csharp
dotnet_naming_style.以_i_开头帕斯卡.required_prefix = I
dotnet_naming_style.以_i_开头帕斯卡.required_suffix =
dotnet_naming_style.以_i_开头帕斯卡.word_separator =
dotnet_naming_style.以_i_开头帕斯卡.capitalization = pascal_case
```

### 以 _ 开头帕斯卡

```csharp
dotnet_naming_style.以___开头帕斯卡.required_prefix = _
dotnet_naming_style.以___开头帕斯卡.required_suffix =
dotnet_naming_style.以___开头帕斯卡.word_separator =
dotnet_naming_style.以___开头帕斯卡.capitalization = pascal_case
```

### 驼峰

```csharp
dotnet_naming_style.驼峰.required_prefix =
dotnet_naming_style.驼峰.required_suffix =
dotnet_naming_style.驼峰.word_separator =
dotnet_naming_style.驼峰.capitalization = camel_case
```

### 以 _ 间隔全部大写

```csharp
dotnet_naming_style.以___间隔全部大写.required_prefix =
dotnet_naming_style.以___间隔全部大写.required_suffix =
dotnet_naming_style.以___间隔全部大写.word_separator = _
dotnet_naming_style.以___间隔全部大写.capitalization = all_upper
```

### 以 Event 结尾帕斯卡

```csharp
dotnet_naming_style.以_event_结尾帕斯卡.required_prefix =
dotnet_naming_style.以_event_结尾帕斯卡.required_suffix = Event
dotnet_naming_style.以_event_结尾帕斯卡.word_separator =
dotnet_naming_style.以_event_结尾帕斯卡.capitalization = pascal_case
```

## 命名规则

### 类名

```csharp
dotnet_naming_symbols.类名.applicable_kinds = class
dotnet_naming_symbols.类名.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.类名.required_modifiers =
```

### 接口

```csharp
dotnet_naming_symbols.接口.applicable_kinds = interface
dotnet_naming_symbols.接口.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.接口.required_modifiers =
```

### 结构体

```csharp
dotnet_naming_symbols.结构体.applicable_kinds = struct
dotnet_naming_symbols.结构体.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.结构体.required_modifiers =
```

### 枚举

```csharp
dotnet_naming_symbols.枚举.applicable_kinds = enum
dotnet_naming_symbols.枚举.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.枚举.required_modifiers =
```

### 委托

```csharp
dotnet_naming_symbols.委托.applicable_kinds = delegate
dotnet_naming_symbols.委托.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.委托.required_modifiers =
```

### 事件

```csharp
dotnet_naming_symbols.事件.applicable_kinds = event
dotnet_naming_symbols.事件.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.事件.required_modifiers =
```

### 方法

```csharp
dotnet_naming_symbols.方法.applicable_kinds = method
dotnet_naming_symbols.方法.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.方法.required_modifiers =
```

### 静态方法

```csharp
dotnet_naming_symbols.静态方法.applicable_kinds = method
dotnet_naming_symbols.静态方法.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.静态方法.required_modifiers = static
```

### 属性

```csharp
dotnet_naming_symbols.属性.applicable_kinds = property
dotnet_naming_symbols.属性.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.属性.required_modifiers =
```

### 公开字段

```csharp
dotnet_naming_symbols.公开字段.applicable_kinds = field
dotnet_naming_symbols.公开字段.applicable_accessibilities = public
dotnet_naming_symbols.公开字段.required_modifiers =
```

### 公开静态字段

```csharp
dotnet_naming_symbols.公开静态字段.applicable_kinds = field
dotnet_naming_symbols.公开静态字段.applicable_accessibilities = public
dotnet_naming_symbols.公开静态字段.required_modifiers = static
```

### 私有静态字段

```csharp
dotnet_naming_symbols.私有静态字段.applicable_kinds = field
dotnet_naming_symbols.私有静态字段.applicable_accessibilities = internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.私有静态字段.required_modifiers = static
```

### 私有/内部/受保护字段

```csharp
dotnet_naming_symbols.私有_内部_受保护字段.applicable_kinds = field
dotnet_naming_symbols.私有_内部_受保护字段.applicable_accessibilities = internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.私有_内部_受保护字段.required_modifiers =
```

### 局部变量

```csharp
dotnet_naming_symbols.局部变量.applicable_kinds = local
dotnet_naming_symbols.局部变量.applicable_accessibilities = local
dotnet_naming_symbols.局部变量.required_modifiers =
```

### 常量

```csharp
dotnet_naming_symbols.常量.applicable_kinds = field
dotnet_naming_symbols.常量.applicable_accessibilities = public, internal, private, protected, protected_internal, private_protected
dotnet_naming_symbols.常量.required_modifiers = const
```

### 参数

```csharp
dotnet_naming_symbols.参数.applicable_kinds = parameter
dotnet_naming_symbols.参数.applicable_accessibilities = *
dotnet_naming_symbols.参数.required_modifiers =
```
