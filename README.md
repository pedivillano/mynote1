# mynote1
appcenter test run uitest --app "pedi/Xamarin-App" --devices "pedi/experiment1" --app-path C:\work\com.companyname.app1.apk --test-series "master" --locale "en_US" --build-dir C:\Users\admin\source\repos\App1\UITest2\bin\Debug --uitest-tools-dir C:\Users\admin\.nuget\packages\xamarin.uitest\3.2.2\tools

for /l %i in (0,1,999) do @set /a "skip=%i*CHUNK_SIZE" & @fsutil file createnew temp\split%ii CHUNK_SIZE & @fsutil file setvaliddata temp\split%ii CHUNK_SIZE & @dd if=RELEASE_FILE_LOCATION of=temp\split%ii skip=%skip% bs=1 count=CHUNK_SIZE
