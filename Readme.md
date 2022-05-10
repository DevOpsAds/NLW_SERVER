**
 * single responsibility principle
 * Open/Closed  Principle
 * Liskov Substitution Principle
 * Interface Segregation Principle
 * Dependency Inversion Principle
 * 
 * 
 * cada classe tem uma responsabilidade única;
 * As classe da aplicalção deve ser abertas para extensão mas fechadas par modificação ;
 * nós devemos poder substituir uma class pai por uma herança dela e tudo continuar funcionado;
 * segregar maior quantidade de classes possíveis para
 * bopra aplicar no código;
 * 
 */

# npm run dev
# npm run start.

` maiores infomaçoes do ajuste para deploy`

* criação de um file name: procfile
o mesmo  após deploy carrega comandos para o servidor
atualmente setado o comando :web: npm run start <--->
-porém durante o deploy por um vez estando o banco de dados postgres já em pronto serviço de nuvem o mesmo subiu com o comando: npx prisma migrate deploy  ---comando para rodar as migrates e criar banco em serviço de servidor 
- tambem foi feito ajustes em listen 3000||PORT
----------------------------
no sevidor heroku foi subir o arquivo por linha de comando git para o servidor da heroko e setar variaveis de abiente 
nem preciso foi muito o mesmo ja preparou o ambiente mais vale apena conferir em:

# Config Vars
Config vars change the way your app behaves. In addition to creating your own, some add-ons come with their own.
Hide Config Vars
Config Vars
DATABASE_URL
postgres://mdelgqfzmotauh:e254ce150ba84b6f5533fbb0e8c75ba8eed05b2d0f4ef3e059f29d2b70fc7794@ec2-34-236-94-53.compute-1.amazonaws.com:5432/d130ffb0n051e5
Edit Delete
KEY
VALUE
Add

' ________________________
ajustes em informações prisma de sqlite para postgresql sem muita coisa foi praticamente seguir o basic the  documents. 

