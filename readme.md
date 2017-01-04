# ActPup extension for OpenSesame

Copyright 2016-2017 Sebastiaan Mathôt

## About

*ActPup* is an extension for OpenSesame that tweaks the OpenSesame interface and monitors how this affects your typing performance (anonymously, of course). This will allow us to better understand what makes user interface good, and why.

To participate, you need to install an extension in OpenSesame. Afterwards, you can continue using OpenSesame as you normally would. The extension will not interfere with your work.

## Installing the extension

- Start OpenSesame. If you're using Windows, you may have to start OpenSesame as administrator. You can do that by right-clicking on the OpenSesame icon in the start menu, and selecting 'Run as administrator'.
- In OpenSesame, show the debug window (`Ctrl+D`)
- In the debug window, execute the following two lines:

~~~ .python
import pip
pip.main(['install', 'opensesame-extension-actpup'])
~~~

- Restart OpenSesame.
- You now see a welcome message. To participate, simply indicate your expertise level as a Python programmer!

## Stopping the experiment

The experiment stops when it is remotely disabled. When this happens depends on the success of the experiment, but the experiment will run for at least several months.

To drop out of the experiment yourself:

- Open the extension manager (Menu → Tools → Plug-in and extension manager)
- Disable the `actpup` extension
- Restart OpenSesame

## Ethics and privacy

We store the number of keys that you press while working with OpenSesame.

- We don't store which keys you press, only whether they are letters, punctuation characters, etc.
- We do not log the order in which you press keys, only how often they are pressed within a certain time.
- We collect your key presses while you develop an experiment, not those of participants while they run an experiment.

From this information, we will not be able to tell what you do with OpenSesame. Your anonymity is guaranteed.

This experiment is conducted by Sebastiaan Mathôt, and has been approved by the ethics committee of the Department of Psychology of the University of Groningen.

## License

`opensesame-extension-actpup` is licensed under the [GNU General Public License
v3](http://www.gnu.org/licenses/gpl-3.0.en.html).1
