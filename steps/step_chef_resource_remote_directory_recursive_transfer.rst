.. This is an included how-to. 

To recursively transfer a directory from a remote location:

.. code-block:: ruby

   # create up to 10 backups of the files, set the files owner different from the directory.
   remote_directory "/tmp/remote_something" do
     source "something"
     files_backup 10
     files_owner "root"
     files_group "root"
     files_mode 00644
     owner "nobody"
     group "nobody"
     mode 00755
   end

