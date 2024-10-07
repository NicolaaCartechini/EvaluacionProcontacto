## Ejercicio 5

### 1 -	Lead

Un lead es una persona o entidad que ha mostrado interés en los productos o servicios de una empresa.
Datos estándar: First Name, Last Name, Company ,Email, Phone, Status y Rating. Puede convertirse en una cuenta o contacto, y puede tener oportunidades asociadas.

### 2 - Account

Una cuenta representa a una empresa o una entidad con la que tienes una relación comercial. Datos estándar: Account Name, Type, Industry, Annual Revenue, Phone y Website. Tiene muchos contactos y oportunidades. Puede tener activos (Assets) y casos (Cases) asociados.

### 3 - Contact

Un contacto es una persona asociada con una cuenta. Datos estándar: First Name, Last Name, Email, Phone y Account Name. Pertenece a una cuenta y puede estar asociado a oportunidades y casos.

### 4 - Opportunity

Una oportunidad es un potencial negocio en el que se está trabajando. Datos estándar: Opportunity Name, Account Name, Stage, Close Date y Amount. Se asocia a una cuenta, puede tener varios productos (Products) y ser parte de un presupuesto (Quote).

### 5 - Product

Un producto es un artículo que se vende o se ofrece en una oportunidad. Datos estándar: Product Name, Product Code, Description y Family. Se relaciona con precios en una lista de precios (PriceBook) y se puede incluir en presupuestos (Quote).

### 6 - PriceBook

Un PriceBook es una lista de precios para productos y servicios. Datos estándar: Name, Description y Is Active. Puede contener múltiples productos y se asocia a oportunidades y presupuestos. 

### 7 - Quote

Un presupuesto es una oferta formal de productos y servicios. Datos estándar: Quote Name, Opportunity, Account y Status. Se relaciona con una oportunidad y puede contener productos y precios.

### 8 - Asset

Un activo es un artículo vendido a un cliente que se puede rastrear a través del ciclo de vida. Datos estándar: Asset Name, Serial Number, Account y Product.
Está asociado a una cuenta y a productos.

### 9 - Case

Un caso es un problema o solicitud de un cliente que necesita atención. Datos estándar: Case Number, Subject, Status, Priority y Account. Se puede asociar a una cuenta y un contacto.

### 10 - Article

Un artículo es un documento o contenido que se puede utilizar para ayudar a resolver un caso. Datos estándar: Title, Summary, Body y Article Number.

![alt text](<../Screenshots/diagrama uml.drawio.png>)