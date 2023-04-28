# creating virtual environment in windows
virtualenv myenv
myenv\Scripts\activate
deactivate


curl -X POST http://mp3converter.com/login -u chirag2010nyc@gmail.com:admin
curl -X POST -F 'file=@./test.mp4' -H 'Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1c2VybmFtZSI6ImNoaXJhZzIwMTBueWNAZ21haWwuY29tIiwiZXhwIjoxNjgyMDk4MzU4LCJpYXQiOjE2ODIwMTE5NTgsImFkbWluIjp0cnVlfQ.neowM4lmp9tWZSquQ6-ngHF4Ch8Ul5qqMMdQOekNHrU' http://mp3converter.com/upload