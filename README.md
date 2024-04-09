![Additional Accessories Kit](https://i.imgur.com/NDbeKWF.png)

# Additional Accessories Kit - Final Version

This is the software for creating support parts for cat ears (file `up0174.zip`). With effort, you can create something decent.

## Tools Included

- `MpetMqo.exe`: Creates mqo data from mpet files (supports pet data and bug fixes).
- `AddMpet.exe`: Adds mqo data to mpet files (supports pet data and bug fixes).

## Usage Instructions

### MpetMqo.exe

Drag and drop mpet (or pet) files directly onto the executable, or use the command in the DOS prompt: `MpetMqo.exe file_name.mpet`. The mqo file will be created in the same folder as the original mpet (or pet) file.

### AddMpet.exe

Important: It is only possible to create vertices with 100% bone influence. It is not suitable for creating objects that need to adhere smoothly and deform with the body. Think of this as suitable for creating simple accessories. Moreover, all objects must be made of triangular faces; do not forget to convert square faces into triangles before adding to mpet. Smoothing is also fixed at 180 degrees, so use an edge-splitting plugin if you need sharp angles.

## Preparation

1. First, create the mqo data for the desired part using `MpetMqo.exe`.
2. Open the mqo file in Metasequoia and create a new object.
3. Change the order and bring the object to the top of the object panel.
4. Create the object you want to mount.
5. Use only textures that are already in the mpet file.
6. Convert all faces to triangular when finished.

## Skeleton Setup

As mentioned, you can only create objects with 100% bone influence. Ignore the "anchor" object created by `MpetMqo.exe`; it is just a creation range for those who want to move with Mikoto and is not related to this kit. It might be better to use the Mikoto-compatible anchor setup, but it is complicated, so skip it.

1. Make a copy of the created object.
2. Change the order and place the copy of the object immediately below the original (second position from the top).
3. Set the bone name material to the duplicated object.

Once done, your work in Metasequoia is complete. Save and close.

## Final Steps

Place the original mpet (or pet) file and the mqo file in the same folder, and using `AddMpet.exe`, drag and drop an mqo or mpet (or pet) file to create a file with extension (*.new). Rename and use as necessary.

## Note

- Do not contact the manufacturer under any circumstances.
- Do not redistribute any of the items included in this kit (executable files, HTML, or images).
- Do not redistribute the original mpet (or pet) files or the mqo data created with `MpetMqo.exe`.
