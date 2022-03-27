# employee_manager_crud

Aplicação de cadastro de empregados. Backend desenvolvido com Spring boot e frontend desenvolvido com React.

![employee_manager-app](https://user-images.githubusercontent.com/86566715/158877759-92585d85-5314-4efa-bcdc-3ccacfb5c139.PNG)

Hospedagem do Backend foi feita no Heroku.

#Requisições

# GET
 https://employee-manager-crud.herokuapp.com/api/v1/employees
 
 # POST
  https://employee-manager-crud.herokuapp.com/api/v1/employees
-Body:
 ```
 {
        "firstName": "Davi",
        "lastName": "Farias",
        "emailId": "davifarias@gmail.com"
    }
 ```   
  # UPDATE E DELETE
  https://employee-manager-crud.herokuapp.com/api/v1/employees/ "ID DO EMPREGADO"
