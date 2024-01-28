class Renting_Sequence{
    Welcome_Greeting(){
        var greeting = console.log("Welcome to Aoura Binge\nBelow is a list of our Movie Database")
            return greeting
    }
    Catalogue(){
        console.log(this.list)
    }
    


    static Category(){
        cat =  "PG 13\nViewer Discresion is Adviced"
    }
    list ={"Avatar": "Year : 2009 \nPrice : $100 ",
          "Saltburn":"Year : 2023\nPrice : $170",
          "Avatar2":"Year : 2020\nPrice : $100",
          "Titanic":"Year : 1997\nPrice : $80",
          "The Nest":"Year : 2020\nPrice : $180",
          "Spiderman2":"Year : 2018\nPrice : $120",
          "Spiderman1":"Year : 2016\nPrice : $100",
          "All Of Us Strangers":"Year : 2024\nPrice : $300"
        }
    




    get_movie_price_List(){
        console.log(this.list)
    }

    Set_movie_option(object,row){
        return Object.values(object).find(x => object[x] === row.key)

        
     
    }
    
}

dope = new Renting_Sequence()
//console.log(dope.get_List())
//console.log(dope.set_Movie(Avatar))
console.log(dope.Welcome_Greeting())
console.log(dope.Catalogue())
const prompt = require("prompt-sync")({sigint : true});

const config = {promptMessage:"Type in Movie of choice"};
const c = prompt(config.promptMessage)
console.log("You have Selected","\n",c)
console.log(dope.Set_movie_option(dope.list,c))

const prompt2 = require("prompt-sync")({sigint : true});

const config2 = {promptMessage:"Rent Movie?(Yes/No)"};
const c2 = prompt2(config2.promptMessage)
if (c2 == "Yes"){
    console.log("Adding",c,"To Drawer\nThanks for using our services")

}else if(c2 == "No"){
    console.log("Check Back with us later , Bye!")
    
}else{
    console.log("Invalid Selection")
    return c
}

  
