# Information about junior javascript developer (me) : 

1. Sergey Guchok (In passport - Siarhei Huchok)
2. Contacts :
    telegram username : @WhoAmI_tg
    discord username : WhoAmI#8674
    vk: https://vk.com/id301181471
    skype: sergey.guchok.vileyka
    cell phone: +375336349157
3. Throughout these courses i want to learn as much as possible. I`m ready to work hard and put 100% of my efforts into it. It is going to be hard but i am ready for this! 
4. My skills are :
    JavaScript core
    React
    Git
    C++ basics
    NodeJS
5. This is the code form my last task 'mentor-dashboard':
```javascript
class App extends Component {
  state = {
    selectedOption: JSON.parse(localStorage.getItem('mentor')) || null,
  }

  handleChange = (selectedOption) => {
    localStorage.setItem('mentor', JSON.stringify(selectedOption));
    this.setState({ selectedOption });
  }
  render() {
    console.log(this.state);
    return (
      <main className="main">
        <MentorSelect onChange={this.handleChange} options={json.mentors} value={this.state.selectedOption} />
        <MentorTable data={json} mentor={this.state.selectedOption}/>
        <Legend />
      </main>
    )
  }
}
```
6. Experience: I was studying in the previous round of RSSchool, you can check my code here: [GitHub](https://github.com/SergeyGuchok?tab=repositories)
7. BSUIR student, 2nd course. 
8. English level: B2
