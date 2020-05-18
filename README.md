# Tribute-Page-CSS

body {
            font-family: Helvetica, sans-serif;
            background-color: lightslategray;
        }

        h1 {
            font-size: 22px;
        }

        h2 {
            font-size: 16px;
        }

        #main {
           /* display: flex;
            flex-direction: column;*/
            
            
            margin-left: 10%;
            margin-right: 10%;
        }

        #header {
           /* display: flex;
            flex-direction: row;
            flex-wrap wrap;*/
            
        }

        #title {
           /* display: flex;
            flex-direction: row;
            flex-wrap: nowrap;*/
            margin: 0% 5% 0% 5%;
            display: grid;
            grid-template-rows: auto;
            justify-content: center;
            background-color: slategray;
            border-radius: 25px;
        }

        #img-div {
           /* display: flex;
            flex-direction: row;
            flex-wrap: wrap;*/
            display: grid;
            grid-template-rows: 50% 50%;
            padding-top: 2%;
            padding-bottom: 2%;
            
           
        }

        #image {
            max-width: 100%;
            max-height: auto;
            justify-content: center;
        }

        #img-caption {
            height: fit-content;
            font-size: 16px;
            font-style: italic;
            margin-left: 50%;
            margin-right: 25%;
            text-align: justify;
            border:black;
            border-style: none;
            border-width: 1px;
            border-radius: 25px;
            padding: 25px;
            background-color: white;
            box-shadow: box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
            /*figure out how to move up alongside picture*/
        }

        #tribute-info {
            display: grid;
            grid-template-rows: 1;
            justify-content: center;
            list-style: none;
            margin: 0% 20% 0% 20%;
            text-align: justify;
            line-height: 25px;
            /*display: flex;
            flex-direction: row;
            flex-wrap: wrap;*/
        }

        #footer {
          /*  display: flex;
            flex-direction: row;*/
            justify-content: center;
          text-align: center;
        }
