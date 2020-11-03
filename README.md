Address()

Test: It will take user inputted work and home addresses and return the addresses
Expect: function Address(homeAddress, workAddress) {
this.homeAddress = homeAddress;
this.workAddress = workAddress;
}

Contact.protoype.addAddress = function(homeAddress, workAddress) {
this.addresses.push(homeAddress, workAddress);
}

function Contact(firstName, lastName, phoneNumber) {
this.firstName = firstName;
this.lastName = lastName;
this.phoneNumber = phoneNumber;
this.addresses = [];
}
Contact.prototype.addAddress = function(address) {
this.addresses.push(address);
}
function Address(home, work) {
this.home = home;
this.work = work;
}
