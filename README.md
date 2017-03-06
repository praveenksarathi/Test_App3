# Test_App3
Python Test App for PUT


#Application Needs Input

#For Updating Details on particular task :TASK_ID
curl -i -H "Content-Type: application/json" -X PUT -d '{"FIELD":VALUE}' http://localhost:5000/todo/api/v1.0/tasks/TASK_ID

Where FIELD is the field in the collection whose value which you want to update
where VALUE is the data that is to be updated in FIELD
