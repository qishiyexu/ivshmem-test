# ivshmem-test


本工程基于ivpci例子，略作修改。
原项目bar0_addr/bar1_addr/bar2_addr用unsigned int，在64位下会出错，改为resource_size_t.