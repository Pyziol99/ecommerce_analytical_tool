# Logistics analytical tool for online store
Universal analytical tool for online store for logistics management. Designed for a master's thesis project. It consists of 4 modules: 
1. controls, 
2. logistics indicators,
3. sales indicators
4. forecast based on the LSTM neural network.  

![Panel_wybrany produkt](https://github.com/Pyziol99/ecommerce_analytical_tool/assets/105854634/0d557d91-d504-4614-bde4-75a387d55d28)


The tool project involves the creation of a fully functioning dashboard for
online stores based on the PrestaShop database. The data that is generated
by the online store and stored in the database are processed and presented in 
the form of measure of useful business information to support business decisions. 
What is worth should be noted, this is not a tool designed exclusively for a single online store software.
The structure of the source code is divided into two parts so
in order to easily adapt the tool under any online store database,
without having to rebuild the entire tool.
In the first part, SQL queries are generated that retrieve data from the database. 
In the second part, the data is processed
and presented in the form of information, within 4 modules. 
The control module has been placed placed in the side panel, the sales module in the upper left corner, the logistics module
in the lower left corner, and the forecasting model based on LSTM neural network covers the right side of the dashboard.
