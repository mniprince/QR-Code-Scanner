# QR-Code-Scanner
QR Code Scanner for Android Studio

# Features
Auto focus and flash light control
Portrait and landscape screen orientations
Back and front facing cameras
Customizable viewfinder
Kotlin friendly
Touch focus

# Supported formats
##  1D product	  --  1D industrial	     ------2D
    UPC-A	          Code 39	          QR Code
    UPC-E	          Code 93	          Data Matrix
    EAN-8	          Code 128	          Aztec
    EAN-13	          Codabar	          PDF 417
                      ITF	                  MaxiCode
                      RSS-14	
                      RSS-Expanded	
                      
# Usage
dependencies {
    
    implementation 'com.budiyev.android:code-scanner:2.1.0'
    
    implementation 'com.karumi:dexter:6.2.3'
}

Add camera permission to AndroidManifest.xml (Don't forget about dynamic permissions on API >= 23):

\<uses-permission android:name="android.permission.CAMERA" \/>



# ViewS


![Screenshot_20211103-035024](https://user-images.githubusercontent.com/40088619/139959402-57d0450e-b770-4ae3-9ace-43560886acbb.png)


![Screenshot_20211103-035010](https://user-images.githubusercontent.com/40088619/139959411-98122128-451b-4da7-b3b7-41d562b19bb4.png)
