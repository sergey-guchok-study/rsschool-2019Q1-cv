# Information about junior javascript developer (me) : 

Name and surname: Sergey Guchok (In passport - Siarhei Huchok)

Contacts :
1. telegram username : @WhoAmI_tg
2. discord username : WhoAmI#8674
3. vk: https://vk.com/id301181471
4. skype: sergey.guchok.vileyka
5. cell phone: +375336349157

Summary: Throughout these courses i want to learn as much as possible. I`m ready to work hard and put 100% of my efforts into it. It is going to be hard but i am ready for this! 

My skills are :
* JavaScript core
* React
* Git
* C++ basics
* NodeJS

This is the code form my last task 'mentor-dashboard':

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

Experience: I was studying in the previous round of RSSchool, you can check my code here: [GitHub](https://github.com/SergeyGuchok?tab=repositories)
BSUIR student, 2nd course. 
English level: B2
