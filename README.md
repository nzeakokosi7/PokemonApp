# PokemonApp

## Getting Started

### Details of the project structure explained below

- /app/src/main/java/com.example.pokemonapp <br/>
  <span style="font-size:15px; color:grey"> #This is where all the application's directories are contained. </span>
    - /ui
        - /theme <br/>
          <span style="font-size:15px; color:grey"> #Here you'd find classes for Color, shape, theme and type. </span>

    - /utils <br/>
      <span style="font-size:15px; color:grey">
      #Here you'd find constants, helpers like parsers and a generic resouce class file.</br></span>

    - /data
      <br/>
      <span style="font-size:15px; color:grey">  # this directory is responsible for containing everything related to app data like models </br>&nbsp;&nbsp;and providers. </span>

        - /remote <br/>
          <span style="font-size:15px; color:grey">
      # Here you'd find api contracts for handling api calls and responses, </br>&nbsp;&nbsp;you'd also find the network interface class. </span>

        - /models <br/>
          <span style="font-size:15px; color:grey">
      # Here you'd find data classes, or data models responsible for abstracting objects. </span>

    - /modules
      <br/>
      <span style="font-size:15px; color:grey"> # Each module is a collection of related composables which presents a unique feature </br>&nbsp;&nbsp; or provides a unique experience to the user.
      Each module consists of a screen, </br>&nbsp;&nbsp; and its respective view model </br>&nbsp;&nbsp;
      Here's an example <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
        - /PokemonDetailScreen.kt <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            - PokemonDetailViewModel.kt <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

    - /repository
      <br/> <span style="font-size:15px; color:grey"> Here you'd find the app repository for the view models of the various **modules**. </span>

    - MainActivity.kt
      <br/> <span style="font-size:15px; color:grey"> The entry point of the application. </span>

    - PokemonApplication.kt
      <br/> <span style="font-size:15px; color:grey"> The application class file. </span>  