# Canon Printer

#### Canon Printer's IP is currently 192.168.1.252
- To find or confirm, run the following command:

    `sudo lpinfo -l -v`

    and look for:

    ```
    Device: uri = socket://192.168.1.252
        class = network
        info = Canon iR-ADV C5535 52.30
        make-and-model = Canon iR-ADV C5535/5540 UFR II
        device-id = MFG:Canon;MDL:iR-ADV C5535/5540 UFR II;CLS:PRINTER;DES:Canon iR-ADV C5535/5540;CID:CA_XPS_OIP;CMD:LIPSLX,PS,PostScript,PCL,PJL,CPCA;
    ```

#### Driver Installation
- Go to [usa.canon.com](https://usa.canon.com)
- Type *C5535i* in the upper-right corner search bar.
- Select `imageRUNNER ADVANCE C5535i`.
- Select `Drivers & Downloads` under `imageRUNNER ADVANCE C5535i`.
- Select `Generic_Plus_PS3_v2.000_Set-up_x64.exe` and download.
- Driver 7zip archive should self-extract in *Downloads* folder.
- Open extracted folder and run the *Setup* executable installer.
- Use *Custom* setup option and select port `8000`.
    + If port `8000` is not visible in port menu, click `Add port`.
        - Choose TCP/IP option
        - Specify port `8080`

#### Printer Usage
- This printer has multiple trays.
- **Tray 1** holds standard printer paper.
- **Tray 2** holds high-quality paper for printing buttons.
    + Set printer to `1200dpi` for best button quality.
