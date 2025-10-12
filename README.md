# CRM

#service/CustomerService.java
package com.sgc.crm.service;

import com.sgc.crm.entity.Customer;
import java.util.List;

public interface CustomerService {
    List<Customer> getAllCustomers();
    Customer getCustomerById(Long id);
    Customer saveCustomer(Customer customer);
    Customer updateCustomer(Long id, Customer customer);
    void deleteCustomer(Long id);
}
