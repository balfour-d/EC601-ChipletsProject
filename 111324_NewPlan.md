# New Plan
Using a basic circuit from an early EE course taken at Northeastern University, we will demonstrate the benefits of chiplets over monolithic design. The circuit we will be recreating uses high pass filters 
and low pass filters to measure heartbeat and remove all unecessary frequencies for visualization. (circuit information can be seen in EECE2150 Lab 15_16.pdf in main branch)

# Steps
- recreate full circuit on LTSpice
  - Look into replacing throughhole components with board mounted to simulate a PCB versus breadboard design
  - show inputs and outputs of lpf and hpf to compare to individual circuits
- create specific high and low pass filters with same components and demonstrate their function
- measure difference in scale between monolithic design and chiplet design
  - figure out how large a full board versus a singular hpf or lpf would be
- Investigate benefits of using chiplets for this circuit
  - determine relative yield for creating chiplets versus whole board to demonstrate higher yield
    - demonstrate cost efficiency
  - demonstrate easy modifications
- Explain further benefits
  - easy scalability
  - power efficiency
