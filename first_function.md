def make_album(artist_name, album_title, number_of_songs=None)
  """Build a music dictionary"""
  music_build = {'artist': artist_name,
          'album': album_title,
          'songs': number_of_songs
      }

  if number_of_songs:
      music_build['songs'] = number_of_songs
  return music_build

music = make_album('green day', 'dookie', 14)
print(music

music = make_album('alanis morisette', 'jaggel little pill', 11)
print(music)

music = make_album('eagle eye cherry', 'desireless')
print(music)
