# donkeycar: a python self driving library

Donkeycar is minimalist and modular self driving library for Python. It is
developed for hobbyists and students with a focus on allowing fast experimentation and easy
community contributions.

### Possible modifications:
1. TODO: Add ros image stream as a camera option to accomodate a remote visual slam node to consume images from the same stream.
2. TODO: Allow for RGBD image input to behavior cloning model.
3. Maybe: Add GPS PID controller (dependent on adding a GPS and electronic compass)

### Notes:
Using `cv_bridge` on the Jetson Nano with python3 requires building cv\_bridge from source.  Instructions can be found here <https://medium.com/@beta\_b0t/how-to-setup-ros-with-python-3-44a69ca36674>.  Replace the `DPYTHON\_LIBRARY` argument with `/usr/lib/aarch-linux-gpu/libpython3.6m.so`, otherwise everything should work as written.   
