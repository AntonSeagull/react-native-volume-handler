---- So, I'll write here one day ---

import { NativeModules } from 'react-native';
const RNVolumeManager = NativeModules.RNVolumeManager;

RNVolumeManager.hide();
//OR
RNVolumeManager.show();

//These functions block the volume  hub or show it.