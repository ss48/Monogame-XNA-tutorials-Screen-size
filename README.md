# Monogame-XNA-tutorials-Screen-size

public Game1()
      {
        
        graphics = new GraphicsDeviceManager(this);
        
        Content.RootDirectory = "Content";
        
        graphics.PreferredBackBufferWidth = 1800;  
// set this value to the desired width of your window
       
       graphics.PreferredBackBufferHeight = 1800;   
// set this value to the desired height of your window

         graphics.ApplyChanges();
      }
