# gradproj
c-1
## Title
Music Inventory System

## Introduction

## This application does something. - no idea what. 

This Project is designed to manage and organize music related assets such as songs,albums,artists,price,tracks.It is commonly used by the music stores, digital music platforms to streamline inventory tracking and improve operational efficiency.

## It can also be deployed - no idea how.

Configure the Application: Update application.properties with database credentials.
Set Up the Database: Run createTables.sql to create and populate the database.
Build the Application: Use mvn clean package to generate the JAR file.
Run the Application: Execute java -jar target/CompactDiscRestDataBoot-0.0.1-SNAPSHOT.jar.
Access the Application: Open http://localhost:8080 in your browser.
Use Swagger: Access API documentation at http://localhost:8080/swagger-ui.html.

## Monitor it 
 1.Add Spring Boot Actuator
 2.Enable Actuator Endpoints
 3.Access Actuator Endpoints
 4.Use Monitoring Tools: Integrate with tools like Prometheus or Grafana for advanced monitoring and visualization.
function doubleCheese()
{
  console.log('double cheese');
  
}
async function pageLoaded()
{
    console.log('page loaded');
    let ulRef=document.getElementById('ulid')
    console.log(ulRef);
    let newLi=document.createElement('li')
    newLi.innerHTML='god'
    ulRef.appendChild(newLi)
    console.log(newLi);
    
    let cities=['pune','hyd','bngl','tokyo']
    //multiple li elements on the fly
let cityol=document.getElementById('citylist');
cities.forEach((c)=>
{
    let newCity=document.createElement('li')
    newCity.innerHTML=c
    cityol.appendChild(newCity)

})

 let response=await fetch('http://localhost:8888/trades/all')
 console.log(response)
 if(!response.ok)
 {
  console.log('unable to call endpoint');
  
 }
 let data=await response.json()
 console.log(data);
 

}
