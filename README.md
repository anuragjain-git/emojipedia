# emojipedia
Templates for emojipedia website. Want to create an emojipedia start with this.

List of all the emojis and their description:

It can be further modified by :
. Adding search bar
. Add more emojis to the list. If you ask chatgpt to make a list of all the emojis in this format it will create a larger list for you.

const emojipedia = [
  {
    id: 1,
    emoji: "😂",
    name: "Face with Tears of Joy",
    meaning:
      "A face with tears streaming down both cheeks, laughing so hard that it's crying."
  },
  {
    id: 2,
    emoji: "❤️",
    name: "Red Heart",
    meaning: "A classic red heart, used to express love or affection."
  },
  {
    id: 3,
    emoji: "😍",
    name: "Smiling Face with Heart-Eyes",
    meaning:
      "A smiling face with hearts for eyes, expressing love or admiration."
  },
  {
    id: 4,
    emoji: "🤣",
    name: "Rolling on the Floor Laughing",
    meaning: "A face rolling on the floor, laughing hysterically."
  },
  {
    id: 5,
    emoji: "🥰",
    name: "Smiling Face with Hearts",
    meaning:
      "A face with smiling eyes and three love hearts floating above it, expressing extreme happiness or love."
  },
  {
    id: 6,
    emoji: "😊",
    name: "Smiling Face with Smiling Eyes",
    meaning:
      "A smiling face with smiling eyes, conveying a sense of happiness or contentment."
  },
  {
    id: 7,
    emoji: "🙏",
    name: "Folded Hands",
    meaning:
      "Two hands pressed together, typically in a gesture of prayer or pleading."
  },
  {
    id: 8,
    emoji: "😭",
    name: "Loudly Crying Face",
    meaning:
      "A face with a big tear streaming down the cheek, used to convey sadness or hurt."
  },
  {
    id: 9,
    emoji: "😘",
    name: "Face Blowing a Kiss",
    meaning: "A face with puckered lips, blowing a kiss."
  },
  {
    id: 10,
    emoji: "🤩",
    name: "Star-Struck",
    meaning:
      "A face with stars for eyes, indicating excitement or feeling overwhelmed with admiration."
  },
  {
    id: 11,
    emoji: "😉",
    name: "Winking Face",
    meaning:
      "A face with a winking eye and a small smile, indicating humor or flirtation."
  },
  {
    id: 12,
    emoji: "😜",
    name: "Winking Face with Tongue",
    meaning:
      "A face with a winking eye and sticking out its tongue, used to indicate humor or playfulness."
  },
  {
    id: 13,
    emoji: "🤔",
    name: "Thinking Face",
    meaning:
      "A face with a raised eyebrow and a hand on the chin, used to indicate thinking, pondering, or skepticism."
  },
  {
    id: 14,
    emoji: "😔",
    name: "Pensive Face",
    meaning:
      "A sad-looking face with a downturned mouth and eyebrows, indicating sadness or disappointment."
  },
  {
    id: 15,
    emoji: "🤯",
    name: "Exploding Head",
    meaning:
      "A face with an exploding head, used to indicate shock, awe, or disbelief."
  },
  {
    id: 16,
    emoji: "💪",
    name: "Tense Biceps",
    meaning:
      "“You can do that!” or “I feel strong!” Arm with tense biceps. Also used in connection with doing sports, e.g. at the gym."
  },
  {
    id: 17,
    emoji: "🤔",
    name: "Thinking Face",
    meaning:
      "Intended to show a person pondering or deep in thought. Often used to question or scorn something or someone, as if saying Hmm, I don't know about that."
  },
  {
    id: 18,
    emoji: "👍",
    name: "Thumbs Up",
    meaning:
      "An okay sign, turned upright. A thumbs-up gesture indicating approval. Thumbs Up was approved as part of Unicode 6.0 in 2010 under the name “Thumbs Up Sign” and added to Emoji 1.0 in 2015."
  },
  {
    id: 19,
    emoji: "👎",
    name: "Thumbs Down",
    meaning:
      "A thumbs-down gesture indicating disapproval. Thumbs Down was approved as part of Unicode 6.0 in 2010 under the name “Thumbs Down Sign” and added to Emoji 1.0 in 2015."
  },
  {
    id: 20,
    emoji: "👋",
    name: "Waving Hand",
    meaning:
      "The Waving Hand emoji is used almost like a “hello” or “goodbye” greeting. It can also be used to ask someone to wave back or to signal to someone that you’re waving at them. It can also be used in place of a “thank you” gesture."
  },
  {
    id: 21,
    emoji: "🤚",
    name: "Raised Back of Hand",
    meaning:
      "The back of a hand that is raised showing the palm. May be used to represent a stop gesture. Raised Back of Hand was approved as part of Unicode 9.0 in 2016 under the name “Raised Back of Hand” and added to Emoji 3.0 in 2016."
  },
  {
    id: 22,
    emoji: "🖐️",
    name: "Hand with Fingers Splayed",
    meaning:
      "A hand with all fingers and thumb extended. May be used to represent an open hand in various senses. Hand with Fingers Splayed was approved as part of Unicode 8.0 in 2015 under the name “Raised Hand With Fingers Splayed” and added to Emoji 1.0 in 2015."
  },
  {
    id: 23,
    emoji: "✋",
    name: "Raised Hand",
    meaning:
      "A raised hand, showing the reverse side of the palm. May be used to represent an open…"
  },
  {
    id: 24,
    emoji: "🖖",
    name: "Vulcan Salute",
    meaning:
      "A raised hand, with the fingers separated between the ring finger and the middle finger. Spock is known for his famous Vulcan salute, which was actually a modification of a real-life gesture performed by Jewish Kohanim."
  },
  {
    id: 25,
    emoji: "🤷‍♀️",
    name: "Woman Shrugging",
    meaning:
      "Used to indicate a lack of knowledge, confusion, or uncertainty about something."
  },
  {
    id: 26,
    emoji: "🤷‍♂️",
    name: "Man Shrugging",
    meaning:
      "Used to indicate a lack of knowledge, confusion, or uncertainty about something."
  },
  {
    id: 27,
    emoji: "😒",
    name: "Unamused Face",
    meaning:
      "A yellow face with slightly raised eyebrows and a frown, shedding a single, blue tear from one eye down its cheek. May convey a variety of unhappy emotions, including disappointment, frustration, and mild sadness."
  },
  {
    id: 28,
    emoji: "😌",
    name: "Relieved Face",
    meaning:
      "A yellow face with soft, closed eyes, eyebrows raised, and a slight smile. Facebook’s design features a slightly open mouth, as if sighing. Conveys various pleasant feelings, including contentment, calm, peace, and relief."
  },
  {
    id: 29,
    emoji: "🙄",
    name: "Face with Rolling Eyes",
    meaning: "Used to indicate disapproval or annoyance."
  },
  {
    id: 30,
    emoji: "🤢",
    name: "Nauseated Face",
    meaning: "Used to indicate feeling sick or disgusted."
  },
  {
    id: 31,
    emoji: "🤮",
    name: "Face Vomiting",
    meaning:
      "Used to indicate feeling nauseous or disgusted to the point of vomiting."
  },
  {
    id: 32,
    emoji: "🥱",
    name: "Yawning Face",
    meaning: "Used to indicate being tired, sleepy, or bored."
  },
  {
    id: 33,
    emoji: "🥺",
    name: "Pleading Face",
    meaning: "Used to indicate begging, pleading, or puppy-dog eyes."
  },
  {
    id: 34,
    emoji: "🥴",
    name: "Woozy Face",
    meaning:
      "Feeling dizzy, disoriented, or intoxicated; Also used to convey silliness or drunkenness."
  },
  {
    id: 35,
    emoji: "😪",
    name: "Sleepy Face",
    meaning:
      "A yellow face with closed eyes, mouth slightly open, and a blue snot bubble coming from its nose. Shows the face of a sleeping person. Often used to represent boredom, fatigue, sleepiness, or grogginess."
  },
  {
    id: 36,
    emoji: "😷",
    name: "Face with Medical Mask",
    meaning:
      "A yellow face wearing a white surgical mask, as used by health workers in hospitals as well as the general public during a pandemic. May be worn to avoid sickness or spreading airborne diseases. Also worn to avoid sickness or spreading airborne diseases."
  },
  {
    id: 37,
    emoji: "👏",
    name: "Clapping Hands",
    meaning: "Used to indicate appreciation or congratulations."
  },
  {
    id: 38,
    emoji: "🙌",
    name: "Raising Hands",
    meaning: "Used to indicate celebration or excitement."
  },
  {
    id: 39,
    emoji: "👐",
    name: "Open Hands",
    meaning: "Used to indicate openness or a hug."
  },
  {
    id: 40,
    emoji: "🤲",
    name: "Palms Up Together",
    meaning: "Used to indicate prayer or pleading."
  },
  {
    id: 41,
    emoji: "🤝",
    name: "Handshake",
    meaning: "Used to indicate agreement or greeting."
  },
  {
    id: 42,
    emoji: "🦾",
    name: "Mechanical Arm",
    meaning: "Used to indicate strength or power."
  },
  {
    id: 43,
    emoji: "😕",
    name: "Confused Face",
    meaning: "I'm feeling unsure or perplexed."
  },
  {
    id: 44,
    emoji: "😱",
    name: "Face Screaming in Fear",
    meaning:
      "Extreme fear, shock or surprise; Also used to convey screaming or crying in fear."
  },
  {
    id: 45,
    emoji: "🤫",
    name: "Shushing Face",
    meaning: "Used to indicate being quiet, secretive or hush-hush."
  },

  {
    id: 46,
    emoji: "🥵",
    name: "Hot Face",
    meaning:
      "Feeling overheated or hot, possibly due to high temperatures, exercise, or spicy food."
  },
  {
    id: 47,
    emoji: "🥶",
    name: "Cold Face",
    meaning:
      "Feeling cold, shivery or chilly; Also used to convey freezing, snow, or winter."
  },
  {
    id: 48,
    emoji: "💀",
    name: "Skull",
    meaning:
      "Used to indicate death or danger, or as a symbol of horror or humor."
  },
  {
    id: 49,
    emoji: "🤤",
    name: "Drooling Face",
    meaning:
      "Feeling extremely hungry or aroused; Also used to convey desire or attraction."
  },
  {
    id: 50,
    emoji: "🤑",
    name: "Money-Mouth Face",
    meaning:
      "Greedy or wealth; Also used to convey excitement, enthusiasm, or success."
  },
  {
    id: 51,
    emoji: "🤪",
    name: "Zany Face",
    meaning:
      "Crazy or silly; Also used to convey fun, excitement, or wackiness."
  },
  {
    id: 52,
    emoji: "💔",
    name: "Broken Heart",
    meaning: "Used to indicate heartbreak or sadness."
  },
  {
    id: 53,
    emoji: "😢",
    name: "Crying Face",
    meaning: "Used to indicate sadness or disappointment."
  },
  {
    id: 54,
    emoji: "😃",
    name: "Smiling Face with Open Mouth",
    meaning: "I'm happy!"
  },
  {
    id: 55,
    emoji: "😝",
    name: "Squinting Face with Tongue",
    meaning: "I'm being grossed out or teasing."
  },
  {
    id: 56,
    emoji: "😛",
    name: "Face with Tongue",
    meaning: "I'm being playful or joking around."
  },
  {
    id: 57,
    emoji: "🤪",
    name: "Zany Face",
    meaning: "I'm being crazy or goofy."
  },
  {
    id: 58,
    emoji: "😎",
    name: "Smiling Face with Sunglasses",
    meaning: "I'm feeling cool or confident."
  },
  {
    id: 59,
    emoji: "😏",
    name: "Smirking Face",
    meaning: "I'm being sly or suggestive."
  },
  {
    id: 60,
    emoji: "😒",
    name: "Unamused Face",
    meaning: "I'm not amused or unimpressed."
  },
  {
    id: 61,
    emoji: "🦿",
    name: "Mechanical Leg",
    meaning: "Used to indicate strength or power."
  },
  {
    id: 62,
    emoji: "🙁",
    name: "Slightly Frowning Face",
    meaning: "I'm feeling down or disappointed."
  },
  {
    id: 63,
    emoji: "😖",
    name: "Confounded Face",
    meaning: "I'm feeling frustrated or distressed."
  },
  {
    id: 64,
    emoji: "🧐",
    name: "Face with Monocle",
    meaning:
      "A face with a monocle and a furrowed brow. Used to convey a sense of sophistication or superiority, or as a form of playful sarcasm."
  },
  {
    id: 65,
    emoji: "🤌",
    name: "Pinched Fingers",
    meaning:
      'Can represent a "tiny bit" of something or someone. Also used to indicate a "small amount."'
  },
  {
    id: 66,
    emoji: "🌚",
    name: "New Moon Face",
    meaning:
      "A face with a new moon, the first phase of the moon when it is invisible at night. Often used to represent darkness, night, or a dark humor."
  },
  {
    id: 67,
    emoji: "☠️",
    name: "Skull and Crossbones",
    meaning:
      "Represents danger or death, often associated with poison or pirates. Can also symbolize rebellion or nonconformity."
  },
  {
    id: 68,
    emoji: "👽",
    name: "Alien",
    meaning:
      'Often used to represent extraterrestrial life or a fascination with outer space. Can also indicate a sense of being "other" or "alienated" from society.'
  },
  {
    id: 69,
    emoji: "👾",
    name: "Alien Monster",
    meaning:
      "Depicts an alien-like creature with big black eyes and a round head, often representing video game or computer culture. Also used to suggest something is weird or strange."
  },
  {
    id: 70,
    emoji: "💩",
    name: "Pile of Poo",
    meaning:
      'Represents feces or poop, but often used to indicate something is "crap" or of poor quality. Can also be used playfully or humorously.'
  },
  {
    id: 71,
    emoji: "🤡",
    name: "Clown Face",
    meaning:
      "Represents a clown or fool, often associated with silliness, humor, or entertainment. Can also indicate deceit or deception."
  },
  {
    id: 72,
    emoji: "👺",
    name: "Goblin",
    meaning:
      "Depicts a Japanese goblin or troll, often depicted with red or blue skin, a menacing expression, and horns on its head. Can also represent mischief or trickery."
  },
  {
    id: 73,
    emoji: "🗿",
    name: "Moai",
    meaning:
      "Depicts a Moai, a monolithic statue located on Easter Island, often representing ancient or historical culture. Can also indicate steadfastness or resilience."
  }
];
