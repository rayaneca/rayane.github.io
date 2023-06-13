# rayane.github.io
<!DOCTYPE html>
<html lang="eng">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>tp2</title>
    </head>
    <body>
        <h1>rayane web page</h1>
       <h1>formulaire de contact</h1>
       <fieldset >
        <legend>Vos coordonnées</legend>
        <form>
            <label for="email">enter your email</label>
            <input type="email" name="email" >
            <label for="date">birth day:</label>
            <input type="date" name="date" >
            <label for="psudo">enter your psudo :</label>
            <input type="text" name="psudo">
            <label for="name">enter your name :</label>
            <input type="text" name="name">
            <label for="password">enter your password</label>
            <input type="password" name="password">
            <label for="COLOR">what's your feaver COLOR :</label>
            <input type="color" name="COLOR">
        </form>
       </fieldset>
       <fieldset>
        <legend>voter sonhait</legend>
        <form>
            <label>faites un souhait que vous voudries voir exauce:</label>
            <label><input type="radio" name="exauce1" value="riche">Etre riche</label>
            <label><input type="radio" name="exauce2" value="celebre">Etre celebre</label>
            <label><input type="radio" name="exauce3" value="encore_plus_intelligent">Etre encore plus intelligent</label>
            <label><input type="radio" name="exauce4" value="autre">autre..</label>
        
        <br><br>
        <label for="autre">Si "Autre" ,veuillez preciser :</label><textarea rows="8" cols="20"></textarea>
        
            <p>cochez les aliments que vous amiez manger :</p>
            <label><input type="checkbox" name="Frites" value="cat"> Frites</label><br>
            <label><input type="checkbox" name="Steak hache" value="dog">Steak hache</label><br>
            <label><input type="checkbox" name="Epinards" value="fish"> Epinards</label><br>
          </form>
       </fieldset>
        <input type="submit" value="Envoyer">



    </body>
</html>
