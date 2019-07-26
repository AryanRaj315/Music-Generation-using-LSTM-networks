# Music-Generation-using-LSTM-networks
We tried to implement end to end learning and generate music with deep neural nets alone. We used LSTM layers that takes a sequence(in this case 100) as an input and can return either sequences (return_sequences=True) or a matrix.
To calculate the loss for each iteration we used categorical cross entropy. 
# Music21 library
This toolkit provides a simple interface to acquire the musical notation of MIDI files. We create notes, chords and rest objects which was then later converted to a suitable form to be used as an input for our model.
