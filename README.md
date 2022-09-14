# simple_admin_user
 interview task
 
 The DB is in mysql
 
 I have created a private api to create the first active admin user
 i.e: url - http://127.0.0.1:5000/admin/create/api
     
     request in json:
     {
       "email": "admin@admin.com",
       "password": "admin",
       "name": "Test Admin"
     }
     
     response:
     {
        "message": "Admin Created",
        "status": 1
      }

Once you have created a initial user, then you can login onto the url - http://127.0.0.1:5000/admin/login
for user - http://127.0.0.1:5000/user/login
