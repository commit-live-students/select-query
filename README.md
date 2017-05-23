![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# SELECT Query

The SQL SELECT statement is used to fetch the data from a database table which returns this data in the form of a result table. These result tables are called result-sets.

### Syntax

The basic syntax of the SELECT statement is as follows −

        SELECT column1, column2, columnN FROM table_name;

Here, column1, column2... are the fields of a table whose values you want to fetch. If you want to fetch all the fields available in the field, then you can use the following syntax.

        SELECT * FROM table_name;

### Example
The following code is an example, which would fetch the CustomerID, CustomerName and ContactName fields of the customers available in Customers table.

        Select CustomerID, CustomerName, ContactName from greyatom.Customers;

This would produce the following result −

 | CustomerID | CustomerName | ContactName |
 | ---------- | ------------ | ----------- |
 | 1 | Alfreds Futterkiste | Maria Anders |
 | 2 | Ana Trujillo Emparedados y helados | Ana Trujillo |
 | 3 | Antonio Moreno TaquerÃ­a | Antonio Moreno |
 | 4 | Around the Horn | Thomas Hardy |
 | 5 | Berglunds snabbkÃ¶p | Christina Berglund |

If you want to fetch all the fields of the Customers table, then you should use the following query.

        Select * from greyatom.Customers;

 | CustomerID | CustomerName | ContactName | Address | City | PostalCode | Country |
 | ---------- | ------------ | ----------- | ------- | ---- | ---------- | ------- |
 | 1 | Alfreds Futterkiste | Maria Anders | Obere Str. 57 | Berlin | 12209 | Germany |
 | 2 | Ana Trujillo Emparedados y helados | Ana Trujillo | Avda. de la ConstituciÃ³n 2222 | MÃ©xico D.F. | 5021 | Mexico |
 | 3 | Antonio Moreno TaquerÃ­a | Antonio Moreno | Mataderos 2312 | MÃ©xico D.F. | 5023 | Mexico |
 | 4 | Around the Horn | Thomas Hardy | 120 Hanover Sq. | London | WA1 1DP | UK |
 | 5 | Berglunds snabbkÃ¶p | Christina Berglund | BerguvsvÃ¤gen 8 | LuleÃ¥ | S-958 22 | Sweden |

