# flagg-final
place-image-align(rectangle(120, 60, "solid", "crimson"), 
  220, 0, "right", "top", 
  place-image-align(rectangle(120, 60, "solid", "crimson"),
    220, 160, "right", "bottom",
    place-image-align(rectangle(60, 60, "solid", "crimson"),
      0, 0 , "left", "top",
      place-image-align(rectangle(60, 60, "solid", "crimson"), 
        0, 160, "left", "bottom", 
        place-image-align(rectangle(220, 20, "solid", "midnight blue"), 
          110, 80, "middle", "center", 
          place-image-align(rectangle(20, 160, "solid", "midnight blue"),
            80, 80, "middle", "center", 
            empty-scene(220, 160)))))))
