0.1 Overview
• This report summarizes how music processing can bridge the gap between learning
signal processing concepts in class and application of the knowledge to real life
problems
• Introduction to application of Fourier Analysis to analyse properties of music
• We discuss how various software tools can make music processing much more intuitive and fun for students
• We then discuss how to use the Python package librosa to analyse audio files and
applying signal processing concepts to enable broader experimentation
0.2 Motive
Music has always been an integral part of human civilization as a form of recreation. With
advent of digital age, we can enjoy music anytime and from anywhere thanks to digital
representation of audio signals. Signal processing plays a major role in music processing
and the vast amount of math involved can scare newcomers. So intuitive introduction to
music processing using software tools can help students apply concepts taught in class
and attain a better understanding of the scale at which signal processing operates in the
real world. Instructors can incorporate music based examples into an existing course on
signal processing, motivating them to pursue further research and experimentation in the
domain.
An introductory course on signal processing covers a range of topics including Types
of Systems, Fourier Transform, Convolution, Laplace Transform, z-Transform, Filtering,
Sampling and so on. All these concepts can be made easier to understand if handson application is allowed for. Here, we focus on audio representation of acoustic waves
generated by instrument or human voice which are transmitted as pressure variations
through air. We will stick to music(preferably) as human speech has a lot of noise that
might be hard to analyse in the beginning.
