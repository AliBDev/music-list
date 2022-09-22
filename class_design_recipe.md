Music List Class Design Recipe
1. Describe the Problem
Put or write the user story here. Add any clarifying notes you might have.

As a user
So that I can keep track of my music listening
I want to add tracks I've listened to and see a list of them.


2. Design the Class Interface
Include the initializer and public methods with all parameters and return values.
class MusicLibrary
  def initialize
  end

  def add(track)
  # adds track to library
  end

  def list
  # lists contents of library
  end

end

3. Create Examples as Tests
Make a list of examples of how the class will behave in different situations.

# 1
music_library = MusicLibrary.new
music_lirbary.list #=> []

# 2
music_library = MusicLibrary.new
music_library.add("superstar")
music_library.list # => ["superstar"]

# 3
music_library = MusicLibrary.new
music_library.add("superstar")
music_library.add ("WAP")
music_library.list # => ["superstar", "WAP"]


4. Implement the Behaviour
After each test you write, follow the test-driving process of red, green, refactor to implement the behaviour.