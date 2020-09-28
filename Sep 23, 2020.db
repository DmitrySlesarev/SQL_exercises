-- September the 23, 2020
SELECT CustomerName as Name, City as Location, * FROM [Customers];
SELECT * FROM Products AS P, Suppliers AS S WHERE P.ProductID = S.SupplierID;
/* Actually, it's the same with the expression above */
SELECT * FROM Suppliers INNER JOIN Products ON Suppliers.SupplierID = Products.SupplierID;
SELECT * FROM Suppliers AS S INNER JOIN Products AS P ON S.SupplierID = P.SupplierID;
SELECT * FROM [Orders] AS O INNER JOIN [Employees] AS E ON O.EmployeeID = E.EmployeeID AND O.OrderID IN (10248, 10249, 10251);
SELECT COUNT(*) AS [NUNMBER of Countries] FROM (SELECT DISTINCT Country FROM [Customers]);
SELECT C.City, O.OrderDate FROM [Customers] AS C INNER JOIN [Orders] AS O ON C.CustomerID = O.CustomerID;
SELECT Customers.CustomerID, Orders.OrderID, Shippers.ShipperID FROM ((Customers INNER JOIN Orders ON Customers.CustomerID = Orders.CustomerID) INNER JOIN Shippers ON Orders.ShipperID = Shippers.ShipperID);
SELECT * FROM [Customers] LEFT JOIN Orders ON Customers.CustomerID = Orders.CustomerID WHERE Customers.CustomerID IS NOT NULL AND Orders.CUstomerID IS NOT NULL;
