# Hi, I'm Noah 👋🙋‍♂️ 
I'm a Frontend Engineer who loves creating things. In regards to FED, I'm most passionate about optimising accessibility, guiding performance, and ✨ _making pretty things_ ✨

## Discover me around the web 🌏
- View my projects on my [personal website](https://noahwbaldwin.me) 💻🌌
- Check out some [photography](https://www.instagram.com/bokehni/) or [just me](https://www.instagram.com/noahbald/) on Instagram 📸
- Connect with me on [LinkedIn](https://www.linkedin.com/in/noahwbaldwin/) 😎
- Listen to King Krule with me on [Spotify](https://open.spotify.com/user/12101435749) 🎧

## Metadata 👨‍💻
``` jsx
import React from 'react'
import { Human } from 'react-human'

export default const Noah = (props) => {
  const workingOn = [
    "Work things",
    "Oxvg, a Rust alternative to SVGO",
  ]
  const learning = [
    "Painting",
    "Neovim",
    "Rust 🦀",
  ]
  /**
   * TODO: Want to learn
   * Music Composition 🎹
   * Game Development 🎮
   */
  const previousLearning = [
    "Amazon Cognito",
    "Circuitry",
    "Guitar",
  ]
  const interestAndHobbies = [
    "Film Photography 🎞",
    "Investing 🐮",
    "Ancient History & Mythology 🗿",
    "Fitness 🏋",
    "Design & Art 🎨",
  ]
  
  return (
    <Human
      👨‍💻={workingOn}
      👨‍🎓={previousLearning}
      🤔={learning}
      ♟️={interestsAndHobbies}
    >
      😎
      👕
      👖
    </Human>
  )
}
```
