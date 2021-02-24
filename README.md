![Screenshot_2021-02-17-17-09-23-56](https://user-images.githubusercontent.com/57650616/108189547-6f5c4e80-7143-11eb-8c5d-dcc1bd0da75d.jpg)
![Screenshot_2021-02-17-17-09-27-17](https://user-images.githubusercontent.com/57650616/108189553-708d7b80-7143-11eb-9549-93090201f581.jpg)

Fragment

Fragment merupakan sebuah reuseable class yang emngimplement beberapa fitur sebuah activity. Fragment biasanya dibuat sebagai bagian dari sebuah interface. Sebuah fragment harus berada dari suatu antarmuka. Sebuah fragment harus berada di dalam sebuah activity karena mereka tidak dapat berjalan sendiri tanpa adanya activity tempat mereka menempel.

Lifecycle Fragment

Urutan Lifecycle Fragment adalah :
Fragment Start -> OnAttach -> OnCreate -> OnCreateView -> OnActivityCreated -> OnStart -> OnResume -> Fragment Is Running -> OnPause -> OnStop -> OnDestroyView -> OnDestroy -> OnDetach -> FragmentEnd
